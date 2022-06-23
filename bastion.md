# How to create bastion and secure VM access using bastion:

## What is Bastion?
```
- Bastion provides secure RDP and SSH connectivity to all of the VMs in the virtual network in which it is provisioned. 
- Using Azure Bastion protects your virtual machines from exposing RDP/SSH ports to the outside world, 
  while still providing secure access using RDP/SSH.
```
## How to create bastion?

```
- search for the **bastions** resource.
- create the new resource in bastion.
```
**Output:**
![image](https://user-images.githubusercontent.com/91359308/175282707-d7a67bbf-4c51-4bad-9f68-f994f8502e21.png)

![image](https://user-images.githubusercontent.com/91359308/175283032-d0e9f09f-b500-481a-a85e-166135cbe9f5.png)

## Secure VM access using bastion
```
- go to the virtual machine on mentioned bastion(vnet)
- click on connect option
- select bastion
- click on use bastion
- give the username and password in VMs 
```
![image](https://user-images.githubusercontent.com/91359308/175285341-3f0fd3e1-91ff-44ed-bd6f-1286b9ba4369.png)

![image](https://user-images.githubusercontent.com/91359308/175285487-7c7bf8d4-32bf-4770-9c96-228123466ac4.png)

**After Connecting the bastion, We have this output**

![image](https://user-images.githubusercontent.com/91359308/175285950-37fb4fbb-057a-40d7-8e6b-1cd13770de6a.png)

