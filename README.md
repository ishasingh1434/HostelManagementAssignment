# KIET Hostel Management System

A Java-based Hostel Management System developed using JDBC, MySQL and Spring Boot REST APIs.

## Projects

### 1. JDBC + MySQL
A menu-driven Java application implementing:
- Insert hostel student records
- Retrieve students based on hostel name and fee
- Update hostel fee
- Search and modify room details
- Calculate total hostel fees and conditionally delete records

**Technologies:** Java, JDBC, MySQL

### 2. Spring Boot REST API
A RESTful backend application implementing:
- Create hostel student records
- Retrieve all students
- Retrieve students by ID
- Update hostel details
- Delete student records

**Technologies:** Java, Spring Boot, Spring Data JPA, MySQL

## Database

Database name: `hostel_db`

Table: `HostelStudent`

## How to Run

1. Configure MySQL credentials.
2. Run the JDBC project using IntelliJ IDEA.
3. Open the Spring Boot project in IntelliJ IDEA.
4. Configure `application.properties`.
5. Run `HostelManagementApplication.java`.
6. Test REST endpoints using Postman.

