# How to connect App Service and Application Gateway using Servie Endpoint

![image](https://user-images.githubusercontent.com/91359308/175523146-c33d84d2-01ee-463a-95d6-4b99169051de.png)


### Connect App Service and Application gatways using service endpoint
---

#### 1. Create app service resouces
#### 2. Create a application gateway resources

**Basics**

![image](https://user-images.githubusercontent.com/91359308/175524052-0ff6cd36-9b43-447f-ad2a-f667a70ae9dd.png)

**Frontends**

![image](https://user-images.githubusercontent.com/91359308/175524628-f864af4e-1852-47c2-804a-c9ca996f080d.png)

**Backends**

**add the app service pool**

![image](https://user-images.githubusercontent.com/91359308/175525095-0605f4fb-75e8-4e1d-915f-f36a3395d93b.png)

**add the VM pool**
![image](https://user-images.githubusercontent.com/91359308/175525460-27a8d4d9-b062-4171-b239-0f66d61a3899.png)

**Configuration**

**Add the rule for App Services**

![image](https://user-images.githubusercontent.com/91359308/175526259-ffa0867c-3799-4476-a5f8-6ba9b3141559.png)

![image](https://user-images.githubusercontent.com/91359308/175526903-9c70fb01-9160-482b-92e9-064ff0177cc9.png)

![image](https://user-images.githubusercontent.com/91359308/175527291-d0cbd152-f0b9-4f12-9fb4-7e0df4bf607e.png)

![image](https://user-images.githubusercontent.com/91359308/175527503-f5df3ded-aeb2-4e90-9e55-ab0bbc92d3e7.png)

**Add the rule for VM**

![image](https://user-images.githubusercontent.com/91359308/175527887-597ec68a-4148-4c80-953c-587d3d0ee973.png)

![image](https://user-images.githubusercontent.com/91359308/175528068-b143e437-fb31-439c-be91-bd691776db4a.png)

![image](https://user-images.githubusercontent.com/91359308/175528205-580a141f-20d7-4596-900c-d1ff61a4f78a.png)

![image](https://user-images.githubusercontent.com/91359308/175528323-aa6c4df5-b11a-4345-ab2e-e2c1ac64d2b2.png)

**Review and create**

**Create**

#### 3. go to the application gateway virtual network - click on service endpoint 

![image](https://user-images.githubusercontent.com/91359308/175529341-98e6e8a6-74d6-427d-9238-bc6bf4fc0db0.png)

![image](https://user-images.githubusercontent.com/91359308/175529550-8d53c5e6-c77e-411c-bc8f-f807c7aa7dce.png)

#### 4. go to the application gateway related app service - go to networking option - go to access restrictions 

![image](https://user-images.githubusercontent.com/91359308/175536300-54c0de59-fd37-48c4-8942-e8982242f052.png)

![image](https://user-images.githubusercontent.com/91359308/175536448-eaf81d6f-4348-4843-9b9e-f526882dc267.png)

#### 5. After creating the access restriction, go to the app service URL, Click that URL - status is forbidden

![image](https://user-images.githubusercontent.com/91359308/175537462-a91847ff-9cb2-4dea-9c88-4a6ce5efb755.png)


**Because,**
```
All data in the App Service has been transferred to the Appliance gateway.
```












