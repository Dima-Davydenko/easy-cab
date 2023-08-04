# EasyCab

### Project description:

This is a simple web-application that supports authentication, registration and other CRUD operations.

I made this project during an online Java course at Mate Academy. The goal of the project is to consolidate the acquired knowledges in Java Core, JDBC, Java Web and SQL. Competently structure project elements and build interaction between them.

### Features:
* registration like a driver;
* authentication like a driver;
* create/update/delete a car, car’s manufacturer or a driver;
* display list of all manufacturers, cars or drivers;
* add driver to car;
* display list of driver’s cars

### Project Overview:

First register by adding a driver to DB or authenticate if you are already registered.

Authentication takes place by entering a login and password. The password does not have strict requirements and can be any.
After successful authentication, the user as a driver goes to the main page of the application. It contains a list of links for performing CRUD operations on cars, car's manufacturer and drivers.

The user can leave the application by clicking "Logout".

### Technologies used:
- Java 11
- Java Servlet API
- JSP, JSTL
- Maven
- SQL
- Tomcat
- HTML, CSS

### Steps to run the program on your computer:
1. Make sure that following programs are installed:
- Java 11 or higher is required;
- IDE to run the App. I used IntelliJ IDEA Ultimate;
- Maven;
- Tomcat;
- SQL database. For example mySQL;
2. Make fork and open the App in your IDE;
3. Create new schema in your DB. Use information in resources/init_db.sql.
4. Enter all necessary information in the util/ConnectionUtil class;
5. Configure webdriver  Tomcat;
6. Run the App in your IDE;
