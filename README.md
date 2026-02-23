# Spring Boot Demo Application

## Experiment Title
Development of REST API using Spring Boot with H2 Database

## Description
This project is a Spring Boot REST API application developed as part of lab experiment.

It demonstrates:
- Creation of REST endpoints
- Integration with H2 in-memory database
- Usage of Spring Data JPA
- CRUD operations for User and Product entities

## Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
- Postman (for API testing)

## How to Run the Project

1. Clone the repository
2. Open in IntelliJ IDEA
3. Run `DemoApplication.java`
4. Application will start on:
http://localhost:8080

## API Endpoints

   ### Register User
   POST: `/api/user/register`

   ### Get All Users
   GET: `/api/user/all`

   ### Add Product
   POST: `/api/product/add`

   ### Get All Products
   GET: `/api/product/all`

## H2 Database Console
URL: http://localhost:8080/h2-console
JDBC URL: jdbc:h2:mem:demo
Username: sa
Password: password

## Output Screenshots

   ### Application Running
   ![p7](https://github.com/user-attachments/assets/adf2e6e8-4b09-496f-853b-1d8ab5ffe663)

   ### Postman – Register User
   ![p1](https://github.com/user-attachments/assets/1b17e26c-8bce-4b48-a0e9-fabdfc0f9a27)
   ![P2](https://github.com/user-attachments/assets/f6c075fa-89b4-4514-9f45-a725c4f9521a)
   ![p6](https://github.com/user-attachments/assets/6b2d0204-8964-42e5-9172-f85f70b1829e)

   ### H2 Console Output
   ![p3](https://github.com/user-attachments/assets/5493092d-b59e-4bf9-a3c7-a483ec9699cf)
   ![p4](https://github.com/user-attachments/assets/a521efc1-05e4-481a-91f1-afa0518e2296)
   ![p5](https://github.com/user-attachments/assets/2b3cc369-226b-4623-8e54-972021d59a64)



## Author
Prerna 
Course: B.E. CSE 
UID: 23BCS80341
