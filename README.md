# Resto-management With Authentication

:house: **Resto-management**

### ***Framework***
---------
- spring boot

-------------

### ***Project management tool***
-------
- Maven


-----------------
### ***DataBase***
****************
- MySql
****************

### **use of dependency**
-----
- <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-data-jpa</artifactId>
      </dependency>
- <dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-web</artifactId>
     </dependency>

- <dependency>
       <groupId>org.springframework.boot</groupId>
       <artifactId>spring-boot-devtools</artifactId>
	<scope>runtime</scope>
	<optional>true</optional>
	</dependency>
- <dependency>
    <groupId>com.mysql</groupId>
    <artifactId>mysql-connector-j</artifactId>
    <version>8.0.33</version>
 </dependency>

- <dependency>
       <groupId>org.projectlombok</groupId>
       <artifactId>lombok</artifactId>
       <optional>true</optional>
	</dependency>
- <dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-test</artifactId>
     <scope>test</scope>
     </dependency>
<!-- https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation -->
- <dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-validation</artifactId>
	<version>3.0.6</version>
	</dependency>





--------


-------------


### **Run tests**

------

⭕ postman 

:globe_with_meridians: chrome browser

********

### **Data structure And programming language**

-----

 - core java
 
 --------

  :point_down: **Summary**
*****
The Restaurant Management System is a web application built using Spring Boot framework, which provides CRUD operations for managing users, food items, and orders. The system supports three types of users: admin, normal user, and visitor.

User Entity:

The User entity represents a user of the system.
It has the following attributes: username, password, and email.
Normal users can have any email type, while admin users' email must be of the format something@admin.com.
Users can sign up and sign in to access the system.
FoodItem Entity:

The FoodItem entity represents a food item in the restaurant's menu.
It has the following attributes: title, description, price, dummyImage URL, and creation date and time.
Only admin users can create food items.
Order Entity:

The Order entity represents a user's order.
It has the following attributes: orderID, FoodItem ID, quantity, userID, status, and order date and time.
Users can place orders, and each order is associated with a specific user and a food item.
The status of an order can be "created," "dispatched," or "delivered."
Access and Roles:

Admin users have additional privileges compared to normal users and visitors. They can perform administrative tasks such as viewing all users.
Visitor users have read-only access to the system, allowing them to view the menu and other information without signing up or signing in.
Normal users have access similar to visitor users, but they can also place orders.
Overall, the Restaurant Management System provides an interface for users to interact with the system based on their roles. Admin users can manage users and create food items, while normal users can place orders, and visitor users can view the menu. The system maintains the date and time of creation for each entity and uses dummyImage URLs for food items
*****

### **Show your Support** 
****
:star: Thankyou 

****
