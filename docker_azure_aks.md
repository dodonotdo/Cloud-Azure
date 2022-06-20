`How to create docker image and container,`
`How to move on the docker cotainer in azure portal,` 
`How to create container registry using vs code,`
`How to create kubernetes sevice using container registry in azure`

### How to build the docker images using VScode
![image](https://user-images.githubusercontent.com/91359308/174544153-49d5713b-d476-4379-bda3-376f9a963998.png)

### How to run the docker container using docker images.
![image](https://user-images.githubusercontent.com/91359308/174544612-a3784788-86a4-444b-903b-aff976ef1102.png)

### After Create the container, Push the container into container registry using azure
`1.create the container registry`

![image](https://user-images.githubusercontent.com/91359308/174545085-2324f669-d90e-48c0-aa56-f23d2e059591.png)

`2. Enter the Regitry name`

`3. Select the SKU`

`4. Select the resource group for new resources`

`5. The container resources will be created`

### After Creating the container registry, go to the azure portal and check container registry
![image](https://user-images.githubusercontent.com/91359308/174546565-edd118ff-eac6-413e-adb6-d08fc65fb9f5.png)

### Link the container registry into kubernetes service
`1. Create the kuernetes cluster Service in azure`
![image](https://user-images.githubusercontent.com/91359308/174547602-928f9d8b-2868-493b-a2e5-0b8ba1144177.png)

`2. link the existed container registry into kubernetes cluster`
![image](https://user-images.githubusercontent.com/91359308/174547930-d2fee68b-8a33-41dc-a92a-1382f88633d3.png)

`3. Review + Create`

`4. After Creating the kubernetes cluster, check it the cluster`
![image](https://user-images.githubusercontent.com/91359308/174548640-dd402cf2-b5d0-4486-bdab-3000281dac56.png)


### how to create kubernetes pods

`1. go to the terminal`

`2. type in az login`

`3. type in az aks get-credentials --resource-group event-notification(resource group name) --name event-aks(this is kubernetes cluser)`

`4. check the pods details using this command, kubectl get pods`




