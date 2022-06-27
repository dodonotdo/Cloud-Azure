### What is Azure Application Gateway?
```
- Azure Application Gateway is a web traffic load balancer that enables you to manage traffic to your web applications. 
- Traditional load balancers operate at the transport layer (OSI layer 4 - TCP and UDP) and route traffic based on source 
  IP address and port, to a destination IP address and port.
- Application Gateway can make routing decisions based on additional attributes of an HTTP request, for example 
  URI path or host headers. 
- For example, you can route traffic based on the incoming URL. So if /images is in the incoming URL, you can route 
  traffic to a specific set of servers (known as a pool) configured for images. 
- If /video is in the URL, that traffic is routed to another pool that's optimized for videos.
```
![image](https://user-images.githubusercontent.com/91359308/175523146-c33d84d2-01ee-463a-95d6-4b99169051de.png)


## Application gateway and Functions:

```
- Functions apps are basically App Services
- They can be protected by Application gateway the same way app services are
- Configure in backend pool
- Configure Access Restricitons
```
