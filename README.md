# Assignment 2 - CPSC 449

## Bookstore MongoDB API

This project implements role-based authorization using Spring Boot, MongoDB, and JWT authentication.

### Features
- User registration and login using JWT authentication
- Role-based access control
- USER role can create books
- ADMIN role required to delete books
- MongoDB database integration

### Technologies Used
- Java
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- MongoDB
- Maven
- Postman

### API Endpoints Tested

#### Authentication
POST /api/auth/register  
POST /api/auth/login  

#### Books
GET /api/books  
POST /api/books  
DELETE /api/books/{id}  

### Authorization Rules
- Anyone can view books
- USER can create books
- ADMIN can delete books
- USER cannot delete books (403 Forbidden)

### Screenshots Included
1. Admin registration
2. Admin login (JWT token)
3. Admin successfully deletes book (200 OK)
4. User forbidden from deleting book (403 Forbidden)

### Running the Project

Start MongoDB:
