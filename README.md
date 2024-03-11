
# Library Management System

## 1. Introduction

### 1.1 Purpose
A library management system is software designed to manage all the functions of a library. It helps librarians maintain the database of new books and books borrowed by members, along with their due dates. This system completely automates all library activities.

### 1.2 Scope
The system allows librarians to perform basic operations such as adding, updating, and deleting books, managing patron information, and tracking borrowing and returning activities.

### 1.3 Features
- **Book Management (Add, Update, Delete)**
- **Patron Management (Add, Update, Delete)**
- **Borrowing and Returning Books**
- **Display Available Books**
- **Fine Calculation**

## 2. MVC Architecture Overview

MVC (Model-View-Controller) architecture is a design pattern widely used in software development, especially in building user interfaces. Here are the key features and advantages of using MVC architecture:

1. **Modularity and Separation of Concerns:**
   - **Feature:** MVC separates the application into three interconnected components (Model, View, Controller), each with a specific role.
   - **Advantage:** This separation allows for modular development, making it easier to manage, update, and extend different aspects of the application without affecting the others.

2. **Maintainability:**
   - **Feature:** Due to the clear separation of concerns, it's easier to maintain and update the codebase.
   - **Advantage:** Developers can make changes or add new features to one component without affecting the others, reducing the risk of introducing unintended side effects.

3. **Reusability:**
   - **Feature:** Components are designed to be reusable in different contexts.
   - **Advantage:** Developers can reuse models, views, and controllers in other parts of the application or even in different projects, promoting code efficiency.

4. **Scalability:**
   - **Feature:** MVC allows for the scalability of the application by independently scaling the components based on the specific needs of the system.
   - **Advantage:** This flexibility enables efficient resource utilization and better performance, especially in larger and more complex applications.

5. **Testability:**
   - **Feature:** Each component can be tested independently, making it easier to identify and fix issues.
   - **Advantage:** Unit testing and integration testing can be more effective, resulting in a more robust and reliable application.

6. **Adaptability to Change:**
   - **Feature:** MVC is adaptable to changes in requirements or technologies.
   - **Advantage:** When requirements change, developers can modify or add components without overhauling the entire system, making the application more adaptable to evolving needs.

7. **Enhanced Collaboration:**
   - **Feature:** Clear separation of responsibilities facilitates collaboration among developers, designers, and stakeholders.
   - **Advantage:** Teams can work more cohesively, with each team focusing on its specific area of expertise, leading to a more streamlined development process.

8. **Community Support and Standardization:**
   - **Feature:** MVC is a widely adopted design pattern with extensive community support.
   - **Advantage:** Developers can leverage established best practices, libraries, and frameworks that adhere to MVC principles, promoting consistency and standardization in application development.
    
![image](https://github.com/Shabanakhan-2412/Library-Management-System/assets/162796897/dffd2513-9315-4af0-a928-53429bb995e5)


## 2. MVC Architecture Overview

### 2.1 Model
The Model represents the data and business logic of the application. It interacts with the database and manages the application's state.

### 2.2 View
The View is responsible for presenting the data to the user and receiving user input. In this console-based system, it displays information and receives commands from the user.

### 2.3 Controller
The Controller acts as an intermediary between the Model and View. It processes user input, updates the Model, and refreshes the View accordingly.

## 3. Technologies Used

### 3.1 Java
The system is implemented using the Java programming language for its simplicity and platform independence.

### 3.2 JDBC
Java Database Connectivity (JDBC) is employed for connecting the Java application with the SQLite database.

### 3.3 SQL
SQL, or Structured Query Language, is a programming language designed for managing and manipulating relational databases.

## 4. Database Design

### 4.1 Tables
- **Books** (BookID, BookName, Author, Price)
- **Library** (LibraryID, Name, Address, Pincode)

## 5. Setup and Configuration

### 5.1 Prerequisites
- Java Development Kit (JDK)
- SQL Database

### 5.2 Database Setup
- Execute SQL script to create tables and establish initial data.

### 5.3 Project Setup
- Download and compile the Java source files.

  
## 6. Code Implementation

### 1. Insert Book

![image](https://github.com/Shabanakhan-2412/Library-Management-System/assets/162796897/d044ddf0-d1ce-4ec2-9cbd-52bdc18ad94a)

### 2. Remove Book

![image](https://github.com/Shabanakhan-2412/Library-Management-System/assets/162796897/be3cb106-15c0-4e18-975e-2bf69866f39d)

### 3.Update Book

![image](https://github.com/Shabanakhan-2412/Library-Management-System/assets/162796897/78127c03-47b8-4472-a11f-b74c05fa5fde)

### 4. Get Book

![image](https://github.com/Shabanakhan-2412/Library-Management-System/assets/162796897/d34c9fd2-29e8-40b5-b3e2-8523e0bce7e8)


### 5. Exit 

![image](https://github.com/Shabanakhan-2412/Library-Management-System/assets/162796897/7093da4d-4102-4f3e-844e-23a70b460713)




