# 🏢 HR Management System

A console-based HR Management System built using Java, JDBC, and PostgreSQL.

This project helps manage departments and employees while performing CRUD operations and generating employee reports.

## 🚀 Features

### 🏬 Department Management

✅ Add Department

### 👨‍💼 Employee Management

✅ Add Employee

✅ View All Employees

✅ Search Employee

✅ Update Employee

✅ Delete Employee

### 📊 Reports

✅ Department Wise Employees

✅ Highest Salary Employee

## 🛠️ Technologies Used

☕ Java

🔗 JDBC

🐘 PostgreSQL

📦 Object-Oriented Programming (OOP)

📝 SQL

🔍 SQL JOIN Queries

⚡ PreparedStatement

🖥️ Console Application

## 🗄️ Database Design

### Department Table

```sql
CREATE TABLE department(
    dep_id INT PRIMARY KEY,
    dep_name VARCHAR(100)
);
```

### Employee Table

```sql
CREATE TABLE employee(
    emp_id INT PRIMARY KEY,
    emp_name VARCHAR(100),
    emp_salary DOUBLE PRECISION,
    dep_id INT REFERENCES department(dep_id)
);
```

## 📚 Concepts Practiced

✅ OOP (Classes & Objects)

✅ JDBC Connectivity

✅ CRUD Operations

✅ SQL JOIN

✅ Foreign Key Relationship

✅ PreparedStatement

✅ ResultSet Handling

✅ Exception Handling

## ▶️ How to Run

1. Install PostgreSQL
2. Create Database `hrms_db`
3. Create Department and Employee tables
4. Add PostgreSQL JDBC Driver
5. Run `HRManagementSystem.java`

## 🎯 Learning Outcome

This project helped me learn how to build a real-world console application using Java and PostgreSQL with relational database concepts, CRUD operations, and SQL JOIN queries.
