# Homework-5

# Homework 5 - Campus Taskboard API

## Project Description
This project is a Spring Boot REST API that allows users to manage tasks. It supports creating, reading, updating, and deleting tasks. The API also includes input validation using Spring Validation.

## Technologies Used
- Java
- Spring Boot
- Maven
- Lombok
- Spring Validation
- H2 Database
- VS Code REST Client

## How to Run the Application
1. Open the project in VS Code or IntelliJ
2. Open a terminal in the project folder
3. Run:
   .\mvnw.cmd spring-boot:run
4. Open a browser and go to:
   http://localhost:8080/api/tasks

## API Endpoints

### GET all tasks
GET /api/tasks

### GET task by ID
GET /api/tasks/{id}

### Create a task
POST /api/tasks

Example:
```json
{
  "title": "Complete Homework 5",
  "description": "Finish Spring Boot API assignment",
  "completed": false,
  "priority": "HIGH"
}
