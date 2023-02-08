=======
# 🚕 Taxi service 🚕
## Description
The web application is based on JDBC and servlets. The project was implemented by following SOLID principles. Functionality allows you to work with a database of drivers and cars. It contains the following functionality:
- Registration;
- Authentication;
- Creating cars, manufacturers or drivers to database;
- Creating relations between drivers and cars;
- Deleting cars, manufacturers or drivers;
- Deleting relations between drivers and cars.

## Structure 🛠
- taxi
    - controller (all servlets)
    - dao (db logic)
    - exception
    - lib (injector and annotations)
    - model (models: car, driver, manufacturer)
    - service (all bisnes logic)
    - util (connection to db)
    - web.filter
- resourses
- webapp (jsp)
## Used technologies, patterns and principles 💻
- JDBC, servlets, Dependency Injection, OOP, three-tier architecture;
- Tomacat, Java 11, Maven, MySql;
- HTML, CSS, JSP, JSTL, and SQL.
 
## How to run the application locally? 🤔
- Install JDK, any IDE, Tomcat v.9.0.5, MySql;
- Fork this project;
- Open project in IDE
- Run SQL script from resourses folder in MySQL Workbench, IDE or console.
- Configure Tomcat;
- Run program;
- Enjoy!
