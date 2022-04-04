# Taxi Service
![taxi-5](https://user-images.githubusercontent.com/92114777/161527495-69858e04-6f28-416d-8fbd-a522909d4499.jpg)

Taxi Service is a simple Web application made for educational purposes. The application supports CRUD operations 
with DB and proposes partly simulation of data management inside the taxi service.

##Features:
>* driver authorisation;
>* creation/updation/deletion of car manufacturer;
>* creation/updation/deletion of car;
>* creation/updation/deletion of driver;
>* adding driver to car;
>* displaying list of created/deleted manufacturers;
>* displaying list of created/deleted cars;
>* displaying list of created/deleted drivers;
>* displaying list of cars for authorised driver.
## Structure:
>The project implements n-tier architecture and includes:
>* DAOs - Data access layer;
>* Services - Business layer;
>* Controllers - Presentation layer.
## Technologies:
>* JAVA 11;
>* Apache Tomcat;
>* Apache Maven;
>* Apache Log4j2;
>* MySQL;
>* JDBC;
>* Javax Servlet;
>* JSP;
>* JSTL;
>* HTML/CSS;
>* Checkstyle plugin.
## How to run the project:
<strong>REMARK:</strong> for running the program you would need to install MySQL and Apache Tomcat version 9.0.XX.
>1. Configure Apache Tomcat for your IDE;
>2. Run SQL-script from <strong><em>resource/init_db.sql</em></strong> for creating database for the project;
>3. Configure <strong><em>/java/taxi/util/ConnectionUtil.java</em></strong> using your URL, USERNAME, PASSWORD, JDBC_DRIVER;
>4. Configure <strong><em>resources/log4j2.xml</em></strong> <strong>(line 7)</strong> using your ABSOLUTE_PATH to this project;
>5. Run the program and create new driver, manufacturer, car;
>6. Now you can use all the features.
