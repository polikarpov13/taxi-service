# Call a Taxi Online
## Project description:
A simple web application that supports authentication, registration and other CRUD operations.
It can be used if you want to simulate a small taxi company and
keep track of everything you need. For example drivers, cars,
who is driving certain car, who is the manufacturer of the car. 
Also, Filters are implemented in this project, so you will not 
be given the full access without authentication. Moreover, I added 
an init_db.sql file for recreating a DB in any moment you want, 
so you do not need to write it by yourself.
## Features:
- Registration like a driver
- Authentication like a driver
- Create/update/remove a car
- Create/update/remove a manufacturer
- Create/update/remove a driver
- Display list of drivers/manufacturers
- Display list of cars of certain driver
## Getting started:
- Clone project to your local repository
- Install Tomcat if you do not have it
- In class ConnectionUtil(src/main/java/taxi/util) replace stubs in variables(URL, USERNAME, PASSWORD, JDBC_DRIVER) with real data
- If you need add Run Configuration(Tomcat, Local Server)
- Then run the project and enjoy using it
## Technologies:
- Java Core
- Java JDBC
- SQL, MySQL
