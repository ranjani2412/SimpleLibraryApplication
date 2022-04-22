# A simple Spring Boot & Springfox library application
This application manages a database of books and authors 

## Details
 * This application uses the default demo HSQLDB schema to maintain book and authors.
 * It uses Spring Boot to create REST endpoints
 * For the endpoint documentation it uses Swagger2
 * It uses Maven and Java11 to build and run.

## How to run
 * Clone this project
 * Use maven command: `mvn clean verify spring-boot:run`
 * The application should run at `http://localhost:8090`
 * The swagger documentation will be available at `http://localhost:8090/swagger-ui.html#/`