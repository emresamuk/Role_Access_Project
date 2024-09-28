# Project Overview
The application utilizes **Spring Boot** for backend development and **Keycloak** for identity and access management. It defines different user roles (e.g., `user`, `admin`, `super admin`) and restricts access to various endpoints based on these roles. Keycloak is integrated into the application to handle authentication, while role-based authorization is managed through Spring Security.

## Key Features
- **User Authentication and Authorization**: Integrated with Keycloak to authenticate users and assign roles.
- **Role-Based Endpoint Access**: Defined endpoints with restricted access based on user roles.
- **Docker Integration**: Utilized Docker to containerize both the Keycloak server and the Spring Boot microservice.
- **Postman Testing**: Included a Postman collection for testing the endpoints with different user roles.

## Technologies Used
- **Java 21**: Primary programming language for the backend.
- **Spring Boot**: Framework for creating the microservice.
- **Keycloak**: Used for user authentication and role management.
- **Docker**: Containerized the application components for easy deployment.
- **Postman**: Utilized for API testing.

## Project Structure
The project is structured as a Maven-based Spring Boot application, with dependencies configured for Keycloak and Spring Security. An H2 in-memory database is used for data storage during development and testing.

## Additional Notes
This project was developed as my first attempt at implementing role-based access control using Spring Boot and Keycloak. Although it is a basic implementation, it was a valuable learning experience in integrating microservices with Keycloak and understanding role-based access management.
