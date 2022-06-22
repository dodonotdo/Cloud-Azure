# Virtual network peering
```
- Virtual network peering enables you to seamlessly connect two or more Virtual Networks in Azure. 
- The virtual networks appear as one for connectivity purposes. 
- The traffic between virtual machines in peered virtual networks uses the Microsoft backbone infrastructure. 
- Like traffic between virtual machines in the same network, traffic is routed through Microsoft's private network only.
```
Azure supports the following types of peering:

   **1. Virtual network peering:** `Connect virtual networks within the same Azure region.`
   
   **2. Global virtual network peering:** `Connecting virtual networks across Azure regions.`
  
## Below the steps are followed by vnet peerings:
**Example**
1. Create the two virtual network. The name of the virtual network is **VNet-1** and **VNet-2**
2. In VNet-1, go to peering option 
3. click Add => Fill the infromation about peering 
 
step - 1

![image](https://user-images.githubusercontent.com/91359308/174969883-2355c821-866e-4455-9d40-3487cbd601a7.png)

step - 2

![image](https://user-images.githubusercontent.com/91359308/174970258-11c0b74d-8fdc-48a6-b8c7-25eeb1d92260.png)

4. Then successfully connected the two virtual networks.

**Output:**
------------

VNet-1
![image](https://user-images.githubusercontent.com/91359308/174968884-b106f2d8-36f9-4876-9faa-85bcba15c157.png)

VNet-2
![image](https://user-images.githubusercontent.com/91359308/174969264-3af99845-841d-4985-bbe7-f48565f2344b.png)

### How to check terminal

```
ssh username@Public-ip-address
or
ssh username@private-ip-address
```



**Note:**
If you need more infromation refer this document - https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-peering
