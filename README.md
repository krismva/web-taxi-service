# Taxi-Service demo app
### Project description
This demo-project is a web-based application designed as a taxi service management system.
It offers features such as user authentication, registration, and CRUD operations.
Built using Java, Servlet API, JDBC, JSP, HTML, and JSTL.

### Functionality
- register/login as a driver
- create/delete/update a driver
- display all drivers
- create/delete/update a car
- add a driver to a car
- display all cars
- create/delete/update a manufacturer
- display all manufacturers

## Project Structure
This project used 3-layer architecture:
- Presentation layer - Controllers
- Application logic layer - Service
- Data access layer - DAO
- 
## Technologies used:
- Java 17
- JDBC
- Java Servlet API
- JSP
- JSTL
- Tomcat 9.0.76
- MySQL 8.0.33
- Maven

## Run project:
1. Clone this project from GitHub.
2. Install Apache Tomcat version 9.0.xx.
3. Install MySQL.
4. Create the necessary tables in your database from the file init_db.sql.
5. Configure field values to your specific properties in the  src/main/java/taxi/util/ConnectionUtil class
- private static final String URL = "url";
- private static final String USERNAME = "username";
- private static final String PASSWORD = "password";
- private static final String JDBC_DRIVER = "driver";
6. Run the project.
