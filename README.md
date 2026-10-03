# Task Management API ✅

RESTful Task Management system with CRUD operations, built with Spring Boot and MySQL.

### 🚀 Features
- Create, Read, Update, Delete Tasks (CRUD)
- Task status management (PENDING, IN_PROGRESS, DONE)
- User-wise task filtering
- Input validation & global exception handling
- Pagination & sorting
- MySQL integration with JPA
- JUnit tests for service & controller layer

### 🛠 Tech Stack
- Java 17, Spring Boot 3, Spring Data JPA
- MySQL, Maven, Lombok
- JUnit 5, Mockito, Postman

### 🔧 How to Run
1. Clone: git clone https://github.com/vasantha-c-16/Task-Management-API.git
2. Configure MySQL in application.properties
3. Run: mvn spring-boot:run

### 📊 APIs
- POST /api/tasks - Create task
- GET /api/tasks - Get all tasks
- GET /api/tasks/{id} - Get task by ID
- PUT /api/tasks/{id} - Update task
- DELETE /api/tasks/{id} - Delete task

### ✅ Testing
- mvn test for unit tests
- Postman collection included

Backend project for Siemens Gamesa Intern role
