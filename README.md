# Student Management System API

A RESTful API built with Spring Boot for managing student records.

## Tech Stack
- Java 21
- Spring Boot 3.5
- Spring Data JPA
- MySQL 8.0
- Maven
- Lombok

## Features
- Full CRUD operations
- MySQL database integration
- Exception handling with proper HTTP status codes
- Input validation

## API Endpoints

| Method | URL | Description |
|--------|-----|-------------|
| GET | /api/students | Get all students |
| GET | /api/students/{id} | Get student by ID |
| POST | /api/students | Create new student |
| PUT | /api/students/{id} | Update student |
| DELETE | /api/students/{id} | Delete student |

## How to Run
1. Clone the repository
2. Configure MySQL in `application.properties`
3. Run `./mvnw spring-boot:run`
4. API runs on `http://localhost:8080`