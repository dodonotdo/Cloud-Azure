## How to interlink storageAccount to SQL server using Manage Identity

**1. Create Storage Account**

**2. Create SQL server**

**3. Interlink the storage account in SQL server** 
 ```bash
 - go to created SQL server 
 - click auditing 
 - click on enable azure SQL auditing 
 - Enter the storage account details  
 ```
  Select authentication type - (either one select - **manage identity** or **storage access key**)
  
 if you select, storage access key - `The storage account and sql server connected successfully.`
 
 if you select, manage identity - 

 ```bash  
 - create manage identity
 - add a role assignment(IAM) in sotage account using manage identity
 ```
**OUTPUT:**
------------

manage identity in role assignment
![image](https://user-images.githubusercontent.com/91359308/174346490-abe4f36d-f8a3-4aae-9d37-15e5749f7b1b.png)

how to view blob container sql server logs => storage account - containers - click blob container - view the logs details.

![image](https://user-images.githubusercontent.com/91359308/174347256-a080e5a9-a338-4f16-9d73-8cda17350f59.png)



 ---
 

