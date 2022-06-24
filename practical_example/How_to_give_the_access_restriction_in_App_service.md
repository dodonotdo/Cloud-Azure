## How to give the access restriction in App Service
### What is Access Restriciton?
- By setting up access restrictions, you can define a priority-ordered allow/deny list that controls network access to your app. 
- The list can include IP addresses or Azure Virtual Network subnets. 
- When there are one or more entries, an implicit deny all exists at the end of the list.

**Example of access restriction:**
1. Create the app service resource.
2. Click on Networking option under the settings.
3. Click on Access-restriction under the inbound traffic.
4. Click on add rule under the access restrictions.
![image](https://user-images.githubusercontent.com/91359308/175483555-6b06f496-b5e6-4c21-b74c-0b6a0e631904.png)

![image](https://user-images.githubusercontent.com/91359308/175484090-c71826c6-f5ac-41b5-a9cb-554396a2f900.png)

5. Successfully enable access restriction
