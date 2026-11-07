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

### 3. Inventory Management System – JDBC with MySQL

**Course Outcome:** CO4

A menu-driven Java application developed using JDBC and MySQL to manage product inventory.

**Features:**
- Insert product records using PreparedStatement.
- Retrieve products by category with quantity less than 20.
- Sort retrieved products by price in descending order.
- Update existing product stock.
- Search products and modify their prices.
- Calculate total inventory value using `SUM(quantity * price)`.
- Delete products only when their quantity is zero.

**Technologies Used:**
- Java
- JDBC
- MySQL
- PreparedStatement

**Database:** `retail_db`

**Table:** `Product`

### 4. Employee Management REST API – Spring Boot with MySQL

**Course Outcome:** CO5

A RESTful web application developed using Spring Boot, Spring Data JPA and MySQL to manage employee records.

**Features:**
- Create and store employee records.
- Retrieve all employees.
- Retrieve an employee by ID.
- Update employee details.
- Delete an employee by ID.
- Return appropriate HTTP responses for successful operations and missing employees.

**Technologies Used:**
- Java
- Spring Boot
- Spring Web MVC
- Spring Data JPA
- MySQL
- Maven

**Database:** `employee_db`

## Project Setup

### JDBC Project
1. Create the `retail_db` database in MySQL.
2. Create the `Product` table.
3. Configure the MySQL username and password in `DBConnection.java`.
4. Add the MySQL Connector/J dependency or JAR.
5. Run `InventoryManagement.java`.

### Spring Boot Project
1. Create the `employee_db` database in MySQL.
2. Configure database credentials in `application.properties`.
3. Reload Maven dependencies.
4. Run `EmployeeManagementApplication.java`.
5. Test the REST endpoints using Postman.

## REST API Endpoints

| Method | Endpoint | Operation |
|---|---|---|
| POST | `/employees` | Add employee |
| GET | `/employees` | Retrieve all employees |
| GET | `/employees/{id}` | Retrieve employee by ID |
| PUT | `/employees/{id}` | Update employee |
| DELETE | `/employees/{id}` | Delete employee |

## Repository Structure

- `InventoryManagementJDBC/` – JDBC and MySQL implementation.
- `EmployeeManagement/` – Spring Boot REST API implementation.

---
