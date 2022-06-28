## What is Storage Account?
```
- An Azure storage account contains all of your Azure Storage data objects: blobs, files, queues, and tables. 
- The storage account provides a unique namespace for your Azure Storage data that is accessible from anywhere 
  in the world over HTTP or HTTPS.
```

### To view the `created storage account`

![image](https://user-images.githubusercontent.com/91359308/176209788-281a0f15-b319-4330-9df1-adb4d2fc3005.png)

### To Create a `Container`

![image](https://user-images.githubusercontent.com/91359308/176210807-eff2ccae-0957-43cf-9ac4-9e96b113461d.png)

### Go to the inside the container and upload the file

![image](https://user-images.githubusercontent.com/91359308/176212046-6fd0590a-3bdc-4cae-b6ed-d2a0a74da3b0.png)

### Inside the container, If need to change the change access level `private`
```
# Note
1. Inside the container - change access level - If need to select private access - 
  (The output will be visible in the browser using a SAS token.)
```
![image](https://user-images.githubusercontent.com/91359308/176215006-1bffd9af-241c-49de-8d83-d2d369057901.png)

![image](https://user-images.githubusercontent.com/91359308/176219268-29b26375-337b-49e3-b392-123bec5866b9.png)

Go to the browser type the URL - https://demostrr.blob.core.windows.net/images/view1.jpg?sp=r&st=2022-06-28T15:30:09Z&se=2022-06-28T23:30:09Z&spr=https&sv=2021-06-08&sr=c&sig=SYXr%2FGBpwNwKnp9UFYNDZgCRqKwniueI0OT9%2FY3f8FM%3D

### Inside the container, If need to change the change access level `container`

```
# Note
1. Inside the container - change access level - If need to select container    
```
![image](https://user-images.githubusercontent.com/91359308/176222559-e1fac7a4-c0ca-4096-8c30-7e4d6f78f482.png)

![image](https://user-images.githubusercontent.com/91359308/176222883-9078cecf-f136-4117-957f-f532a9431c16.png)




