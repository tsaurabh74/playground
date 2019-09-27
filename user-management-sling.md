# User Management

## Adding new user 

1. Navigate to Users menu.
http://localhost:8080/bin/users.html/

![1 ](https://user-images.githubusercontent.com/46415601/65403427-479f7480-ddf1-11e9-8105-c02cfdce5173.png)




2. Click to add user icon.

![add user](https://user-images.githubusercontent.com/46415601/65403462-7cabc700-ddf1-11e9-9dd1-defe756d62bb.png)


3. Enter Username and Password.


![enter_username_and_pass](https://user-images.githubusercontent.com/46415601/65403482-9220f100-ddf1-11e9-86a2-99d6d01da75d.png)





4. Click on Create button.


![create user](https://user-images.githubusercontent.com/46415601/65403469-86352f00-ddf1-11e9-8ce4-919e06962ba4.png)





## Grant the permissions to user

Once the user is created, the next step is giving the respective permission to the user.
In the example below, we will provide the admin access to user.


1. Navigate to browser menu.
    http://localhost:8080/bin/browser.html/

![browser menu](https://user-images.githubusercontent.com/46415601/65403510-abc23880-ddf1-11e9-9d8d-071f4e5e71ee.png)





2. Click on `jcr:root` .

![click to jcr:root](https://user-images.githubusercontent.com/46415601/65403520-b1b81980-ddf1-11e9-9cf8-f8a0a41d00de.png)


3. Click on grant access icon.

![access rules](https://user-images.githubusercontent.com/46415601/65403527-bc72ae80-ddf1-11e9-840f-dc46b59f9d48.png)


4. Click the plus(+) icon.



![click on plus icon](https://user-images.githubusercontent.com/46415601/65403538-c5fc1680-ddf1-11e9-91f8-fb032e371bbf.png)







5. Enter username in ‘Principle’ block and select the `jcr:all` in Privileges option  to give user the admin access.
Based on your need you may restrict the role of user by adding the Privileges of your choice.



![grant access to the user](https://user-images.githubusercontent.com/46415601/65403838-6acb2380-ddf3-11e9-921f-4b17c04c9f85.png)
