# How to connect App Service and Application Gateway using Servie Endpoint

### What is Azure Application Gateway?

- Azure Application Gateway is a web traffic load balancer that enables you to manage traffic to your web applications. 
- Traditional load balancers operate at the transport layer (OSI layer 4 - TCP and UDP) and route traffic based on source IP address and port, to a destination IP address and port.
- Application Gateway can make routing decisions based on additional attributes of an HTTP request, for example URI path or host headers. 
- For example, you can route traffic based on the incoming URL. So if /images is in the incoming URL, you can route traffic to a specific set of servers 
  (known as a pool) configured for images. 
- If /video is in the URL, that traffic is routed to another pool that's optimized for videos.

![image](https://user-images.githubusercontent.com/91359308/175523146-c33d84d2-01ee-463a-95d6-4b99169051de.png)


### Connect App Service and Application gatways using service endpoint

1. Create app service resouces
2. Create a application gateway resources
**Basics**

![image](https://user-images.githubusercontent.com/91359308/175524052-0ff6cd36-9b43-447f-ad2a-f667a70ae9dd.png)

**Frontends**

![image](https://user-images.githubusercontent.com/91359308/175524628-f864af4e-1852-47c2-804a-c9ca996f080d.png)

**Backends**
add the app service pool

![image](https://user-images.githubusercontent.com/91359308/175525095-0605f4fb-75e8-4e1d-915f-f36a3395d93b.png)

add the VM pool
![image](https://user-images.githubusercontent.com/91359308/175525460-27a8d4d9-b062-4171-b239-0f66d61a3899.png)






