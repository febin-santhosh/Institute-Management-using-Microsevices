# Institute Management System using Microservices

## Overview
The Institute Management System is a modular application built using a microservices architecture to manage the core operations of an educational institution.

The system is designed with independently deployable services, enabling better scalability, maintainability, and flexibility. Service-to-service communication is handled using RabbitMQ, ensuring reliable and asynchronous messaging between components.

Authentication is implemented using ASP.NET Web API, and an MVC-based frontend application provides the user interface. An API Gateway is configured to manage routing, security, and centralized access to backend services.

## Key Highlights
- Microservices-based architecture for modular design
- Asynchronous communication using RabbitMQ
- Secure authentication and authorization using Web API
- API Gateway for centralized request handling
- MVC frontend for user interaction
- Scalable and maintainable system design

## Architecture
The application consists of multiple independent services:

- AuthenticationWebApi — Handles user authentication and authorization
- StudentWebApi — Manages student-related operations
- StudentLibrary — Business logic for student service
- CourseWebApi — Handles course management
- CourseLibrary — Business logic for course service
- BatchWebApi — Handles batch management
- BatchLibrary — Business logic for batch service
- InstituteMvcApp — Frontend MVC application
- InstituteGateways — API Gateway for routing and security

## Technologies Used
- .NET
- ASP.NET Core Web API
- ASP.NET MVC
- RabbitMQ
- SQL Server
- Microservices Architecture
- API Gateway

## Features
- Authentication and authorization
- Student, course, and batch management
- Service-to-service communication using RabbitMQ
- Centralized API Gateway routing
- Modular and scalable architecture

## Project Structure
```text
Institute-Management-using-Microservices/
│
├── AuthenticationWebApi/
├── BatchLibrary/
├── BatchWebApi/
├── CourseLibrary/
├── CourseWebApi/
├── InstituteGateways/
├── InstituteMvcApp/
├── StudentLibrary/
├── StudentWebApi/
├── .gitattributes
├── .gitignore
├── Institute Management using Microservices.sln
├── README.md
└── SqlQuery_1.sql
