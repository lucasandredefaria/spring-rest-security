# Spring Boot API Rest and Security 

This is a small example of an API using Spring Boot + Spring Security and JPA.


## Installation
mvn clean install
mvn spring-boot:run

## use
Send a GET request along with USER/ADMIN login:

	curl localhost:8080/books -u user:password

	curl localhost:8080/books/1 -u admin:password

For you to send a POST, PUT, PATCH or DELETE request, you need to be admin. Otherwise, the 403 - Forbidden error will be displayed.

	



