# Fitness Monolith

A backend Fitness Application built with Java and Spring Boot, providing REST APIs for user authentication, fitness activities, and recommendations.

## 🚀 Features

- User Registration and Login
- JWT-based Authentication
- User and Activity Management
- Fitness Activity Tracking
- Fitness Recommendations
- RESTful APIs
- Global Exception Handling
- PostgreSQL Database Integration
- JPA/Hibernate for Database Operations
- Swagger UI for API Documentation
- Docker support

## 🛠️ Tech Stack

- Java
- Spring Boot
- Spring Security
- JWT
- Spring Data JPA
- Hibernate
- PostgreSQL
- Maven
- Swagger UI
- Docker

## 🔐 Authentication

The application uses JWT (JSON Web Token) based authentication.

Users can register and log in to obtain a JWT token. The token is then used to authenticate protected API requests.

## 📚 API Documentation

Swagger UI is used for interactive API documentation and testing.

## 🗄️ Database

PostgreSQL is used as the database, with Spring Data JPA and Hibernate for persistence and ORM.

## 🐳 Docker

The project includes a Dockerfile for containerized deployment.

## ▶️ Running the Project

1. Clone the repository.
2. Configure the PostgreSQL database.
3. Update the required application properties/environment variables.
4. Build the project using Maven.
5. Run the Spring Boot application.

## 📌 Project Structure

```text
src/main/java/com/project/fitness
├── config
├── controller
├── dto
├── exception
├── model
├── repository
├── security
└── service
