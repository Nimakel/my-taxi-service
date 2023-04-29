# Taxi Service <img src="https://user-images.githubusercontent.com/111348563/230981463-3abdf3c3-a3bc-4c63-a38e-e489324b5725.png" align="left" height="50" width="50">
This project is imitation a taxi service. Project works on Java Servlets and SQL.
# Features
* Add and delete car models
* Add and delete cars
* Add and delete drivers
* Add drivers to specific cars
* View all cars belonging to the current driver
* Authentication
# How to run project
* Clone this repository
* Run SQL script located **src/main/resources/init_db.sql** to initialize database
* Replace the values of the `URL`, `USERNAME`, `PASSWORD` and `JDBC_DRIVER` properties with the appropriate values for your database setup
* Build project by using Maven: *mvn clean package*
* Deploy the WAR file to a servlet container such as Tomcat
* After deploying the project, navigate to http://localhost:8080 in your browser
# Structure
* controller: Servlets that handle HTTP requests and responses
* dao: Data Access Object interfaces and their implementations
* filter: Servlet Filters used to intercept requests and responses
* model: Plain Old Java Objects (POJOs) that represent data
* service: Service interfaces and their implementations that perform business logic
* util: Utility class used in a project to create a database connection
* resources: Non-Java files such as database scripts
* webapp: Contains web resources such as JSP files
* WEB-INF: Contains configuration files for the web application
* views: Contains JSP files used as views in the application for cars, drivers, manufacturers, authentication
# Used Technologies
* Java `v.18.0.2`
* Maven `v.3.8.0`
* JDBC `v.4.2`
* MySQL `v.8.0.22`
* Java Servlets `v.4.0.1`
* Tomcat `v.8.5.87`
# Authors
[Maksym Yashyn](https://www.linkedin.com/in/maksym-yashyn-dnipro/)
