## What is Azure MySQL Database?
```
- MySQL Database on Azure is the MySQL cloud database service that we launched on Azure. 
- It is a type of relational database service that is fully compatible with MySQL protocols, and it gives users a 
  fully managed database service that features stable performance, rapid deployment, high availability, 
  and high levels of security.
```
**Create a Azure MySQL Database:**
![image](https://user-images.githubusercontent.com/91359308/176128973-effde07d-76b7-41ae-9cec-4b85e9313cc4.png)

**View the created Azure MySQL Database:**
---

### Login into the mysql server through `Azure CLI`

In Azure mysql database, 
```
# Note:
- go to the connection security, enable allow access to azure service.
- should not include the client ip in firewall.
- should have enable ssl connection.
- download the ssl certificate and uploade the azure CLI terminal.
```
**After set up the above note, we can execute the following command**

```
mysql -h (hostname) -u (username@servername) -p --ssl-ca=(ssl-certificate-key-name)

ex:
----
mysql -h mysql-demo-sever.mysql.database.azure.com -u ubuntu@mysql-demo-sever -p --ssl-ca=BaltimoreCyberTrustRoot.crt.pem
```
---

### Login to the mysql server thorugh `Client Server`

In Azure mysql database, 
```
# Note:
- go to the connection security, disable allow access to azure service.
- should include the client ip in firewall.
```
**Login to the local mysql server**
```
# Login to the local mysql server
mysql -u root -p

# Create a new user
CREATE USER 'ubuntu'@'mysql-demo-sever' IDENTIFIED BY 'Password@123';

# Grant all the privilages
GRANT ALL PRIVILEGES ON *.* TO 'ubuntu'@'mysql-demo-sever' WITH GRANT OPTION;
```
**After set up the above command, we can execute the following command**
```
mysql -h mysql-demo-sever.mysql.database.azure.com -u  ubuntu@mysql-demo-sever -p
```

