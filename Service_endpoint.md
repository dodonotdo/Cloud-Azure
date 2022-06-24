## What is Service Endpoint?
- Service endpoints provide the ability to **secure Azure service resources to your virtual network** by extending VNet identity to the service. 
- Once you enable service endpoints in your virtual network, you can add a **virtual network rule to secure the Azure service resources** to your virtual network.

**Tips**
```
- Service Endpoint solves this security risk.
- Sometimes these resources are accessed only from resources in the cloud. (ie.)Database in the backbone.
- The traffic never leaves azure backbone.
- although the resource still has a public IP.
- Enable Service endpoint on the subnet from which you want to access the resources.
- on the resources, set the subnet as the source of traffic.
```

![image](https://user-images.githubusercontent.com/91359308/175462055-ae7484ce-fdb9-4fa0-8deb-1de1f76a1f60.png)

**Flowchart of service endpoint:**

![image](https://user-images.githubusercontent.com/91359308/175461699-474e2229-3250-47d1-94fd-79e811e06696.png)

![image](https://user-images.githubusercontent.com/91359308/175461830-ab9b86c7-0579-4438-98ff-156b33e94b5b.png)
