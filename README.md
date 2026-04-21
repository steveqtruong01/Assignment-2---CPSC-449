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

### Screenshots

<img width="866" height="672" alt="Screenshot 2026-04-20 at 9 09 40 PM" src="https://github.com/user-attachments/assets/a37160f0-f8bc-478c-be13-5e013db44415" />
<img width="912" height="495" alt="Screenshot 2026-04-20 at 9 10 38 PM" src="https://github.com/user-attachments/assets/f1862cd9-cd3b-4d39-8957-279115867279" />
<img width="810" height="552" alt="Screenshot 2026-04-20 at 9 10 28 PM" src="https://github.com/user-attachments/assets/6f445c4e-0330-4ec5-9a8c-399bd0a1909f" />
<img width="762" height="733" alt="Screenshot 2026-04-20 at 9 10 18 PM" src="https://github.com/user-attachments/assets/0adcb4b5-57f7-4c1b-80dc-57001b15c704" />
<img width="857" height="645" alt="Screenshot 2026-04-20 at 9 09 58 PM" src="https://github.com/user-attachments/assets/9d122f84-5078-4fe3-92f3-67462c12e410" />

