# testTask
# User API

This is a simple RESTful API in Java using Spring Boot and Spring Data MongoDB to perform CRUD operations on a `User` entity.

## Requirements
- Java 11
- Spring Boot
- Spring Data MongoDB
- Maven
- Docker and Docker Compose

## Build and Run Instructions
1. Make sure you have Java 11, Maven, Docker, and Docker Compose installed on your system.
2. Clone this repository.
3. Navigate to the project directory.
4. Run the following command to build the project and create a Docker image:
5. Start the application and MongoDB containers using Docker Compose:
6. The API will be accessible at http://localhost:8080/users.

## Important Decisions and Assumptions
- The API follows the RESTful design principles and uses the `/users` endpoint for user-related operations.
- The MongoDB database connection URL is specified in the `application.properties` file.
- Clean code practices, such as meaningful variable and method names, separation of concerns, and single responsibility principle, have been followed throughout the project.
- Error handling and appropriate HTTP status codes have been implemented for each API endpoint.
- The User entity is represented by the `User` class with `id`, `name`, and `email` fields.

## Clean Code Principles
1. DRY (Don't Repeat Yourself): Repeated code has been avoided by utilizing Spring Data MongoDB and separating concerns into appropriate classes (e.g., UserController, UserService, UserRepository).
2. SOLID Principles: The code follows SOLID principles by keeping classes focused on a single responsibility, utilizing dependency injection for loose coupling, and adhering to the single responsibility principle.

