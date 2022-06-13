# Connect to a storage account using an Azure Private Endpoint and connecting app registration

### What is Azure Private Endpoint?
- You can use private endpoints for your Azure Storage accounts to allow clients on a virtual network (VNet) to **securely access data over a Private Link**.
- -The private endpoint uses a separate IP address from the VNet address space for each storage account service.

The following steps are followed,

### 1. Create a `virtual network`

### 2. Create a `virtual machine`

### 3.Create a `storage account`

1. After creating a storage account - go to this path

![image](https://user-images.githubusercontent.com/91359308/173288264-32f2b501-3739-4041-b523-4e6febdcbdca.png)

2. After creating a private endpoint, check the storage account. The private end point is added or not in the storage account?
3. if it is added, status is successful.

### 4.Create a `App Registration`

1. Create a app registration account
2. after creating the app registration go to this path for creating a client secret ID ->
**certificate & secret - client secret - new client secret**

![image](https://user-images.githubusercontent.com/91359308/173289485-8e172161-e9d3-44d3-9aa8-65942e27abe7.png)

**How to add the `role assignment` in `resource group` using App ID**

1. go to specified resource group 
2. click on Access Control (IAM) - click on role assignment - click on add - click on add role assignment - then below steps are also followed

3. Whichever one you want, you select it.

![image](https://user-images.githubusercontent.com/91359308/173292079-b3481618-d748-43c8-9fa5-bf8deb51144e.png)

[image](https://user-images.githubusercontent.com/91359308/173290354-b08d7517-7f11-42c9-a30a-672653e18d7b.png)
 
4. go to members and select the app registration id 

![image](https://user-images.githubusercontent.com/91359308/173290742-38f5c9ff-1422-4895-ab6b-cec64a145f5f.png)
5. then, go to reveiw and create . after creating the  role assignment , the role will be added inside the resource group.

### NOTE:
`Resources` ( storage account, VM, and etc....) also followed the same procedure for `role assignment`.

To learn much details, visit this page - https://docs.microsoft.com/en-us/azure/private-link/tutorial-private-endpoint-storage-portal
