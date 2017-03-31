# Product catalog application

Product catalog implement simple CRUD operations with a `Product` entity.

## What's inside 
This project is based on the [Spring Boot](http://projects.spring.io/spring-boot/) project and uses these packages :
- Maven
- Spring Core
- Spring Data (Hibernate & SQLite)
- Spring MVC (Tomcat)
- [Thymleaf](www.thymeleaf.org)

## Installation 
The project is created with Maven, so you just need to import it to your IDE and build the project to resolve the dependencies

## Database configuration 
Create a SQLite database with the name `springbootdb`and add the credentials to `/resources/application.properties`.  
The default ones are :

```
jdbc.driverClassName=org.sqlite.JDBC
jdbc.url=jdbc:sqlite:springboot.sqlite
jdbc.username=
jdbc.password=
hibernate.dialect=org.hibernate.dialect.SQLiteDialect
hibernate.show_sql=true

```

## Usage 
Run the project and head out to [http://localhost:8080](http://localhost:8080)
