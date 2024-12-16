# Configure SQL Server for remote access:

To make sure we can connect through Azure to our local database this are the settings that need to be configured:

1. Create new user, under “Security” > “Users”, right clic and “New User”:

![img/image.png](img/image%205.png)

2. Fill the fields…

![img/image.png](img/image%206.png)

3. Check db_datareader under the Membership tab and clic “OK”

![img/image.png](img/image%207.png)

4. Also ensure that server authentication is on “SQL Server and Windows Authentication mode” and the server allows remote connections. So, to check this we have to right clic on the server:

![img/image.png](img/image%208.png)

![img/image.png](img/image%209.png)

With this steps we have almost everything configured on the local part.

[Siguiente](https://github.com/Daniel-Tajamar/End-to-End-Data-Engineering-Project/blob/main/create-resource-group.md)