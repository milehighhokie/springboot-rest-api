# Simple sample example of Java Springboot
Assuming you have Java and Maven installed
- https://adoptium.net/download/
- https://maven.apache.org/download.cgi

## To execute
- mvn clean install 
- mvn spring-boot:run 

## In a seperate command prompt, you can execute these commands.
- curl -X GET http://localhost:8080/api/users/ 
- curl -X GET http://localhost:8080/api/users/1 
- curl -X POST http://localhost:8080/api/users -H "Content-Type: application/json" -d '{"name": "John Doe", "email": "john.doe@example.com"}' 
- curl -X PUT http://localhost:8080/api/users/1 -H "Content-Type: application/json" -d '{"name": "Jane Doe", "email": "jane.doe@example.com"}' 
- curl -X DELETE http://localhost:8080/api/users/1 

### Errors to avoid
Make sure your CLASSPATH is pointed to the springboot-rest-api\src\main\java\com\example\demo directory
