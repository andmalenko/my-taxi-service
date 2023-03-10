# 🚕 Taxi-Service
## 📖Project description:
```
A simple web-application that may be useful not only for taxi-companies🚖, 
but for any other logistic🚐 🚚 , rental🚗 🚙 🚲, and coworking💻 companies. 
It provides authentication, registration, and other CRUD operations, 
with the ability to add user or users (drivers in this project) 
to the unit (car in this project).
```
## 🍬Features:
- registration user (like a driver);
- authentication user (like a driver);
- create/update/remove a car manufacturer;
- create/update/remove a car;
- create/update/remove a driver;
- display list of all car manufacturers;
- display list of all cars;
- display list of all drivers;
- display list of all cars by current driver;
- add driver to car.
## 📚Project structure (3-layer architecture):
- DAO - Data access layer
- Service - Application logic layer
- Controllers - Presentation layer
## 💻Used technologies and libraries:
- Java 8
- Git
- Apache Maven
- Apache Tomcat
- MySQL
- JDBC
- Javax Servlet
- JSP
- JSTL
- HTML/CSS
- Checkstyle plugin
## ⚙️How to run the program on your computer? Follow steps:
- Clone this: [https://github.com/andmalenko/my-taxi-service](https://github.com/andmalenko/my-taxi-service);
- Install MySQL;
- Configure Apache Tomcat version (**IMPORTANT**): 9.0.xx;
- Copy and run SQL script [/src/main/resources/init_db.sql](/src/main/resources/init_db.sql) to creating a schema and tables for the project;
- Configure [/src/main/java/taxi/util/ConnectionUtil.java](/src/main/java/taxi/util/ConnectionUtil.java) with your URL, USERNAME, PASSWORD, JDBC_DRIVER;
- Run 🚀