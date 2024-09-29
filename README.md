# Simple RESTful Web Service with Spring Boot
 CMPE272 - Lab1

## Short Description
A simple RESTful web service built using Spring Boot. The service exposes an endpoint that returns a greeting message. The `Greeting` class is a model that stores the ID and content of the greeting, and the `GreetingController` handles HTTP GET requests to the `/greeting` endpoint.

## How to Run the Application
### Prerequisites
- Java 11 or above
- Maven 3.6 or above
- IDE (e.g., IntelliJ IDEA, VS Code)

### Steps to Run
1. Open the project in your IDE or terminal.
2. Run the following command to build and run the application:
   ```bash
   mvn spring-boot:run
3. The application will start on the default port 8080.