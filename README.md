# Project Management System

* In this project the emphasis is on the backend - Java Spring Boot and Hibernate.
* The front-end is only used to demonstrate the flow of the application, so it didn't undergo refactoring.
* There was no emphasis on software security: the database data and end-to-end connections are not encrypted.
  Also, username and password for the datasource, and the email service are exposed in the application.properties file. 


To run the application:

Configure the application.properties file (located in: project-management-system-server/src/main/resources/):
- You can change the spring datasource driver to a diffrent driver for a relational database (MySQL by default).
- Change spring datasource url to your desired database url (default database name: project_management_system).
- Create a new username and password for your datasource to be used in this project, and enter them in the properties file (don't use a username and password you don't want to expose)
- Enter the email account and password to be used for sending emails by the application (don't use an account or password you don't want to expose).
