# 📚 Library Management System (SQL Project)

## 🔍 Project Overview
This project is a Library Management System built using SQL as part of my learning and practice in database management.  
The project focuses on understanding relational databases, table relationships, CRUD operations, and analytical SQL queries using a real-world use case.  

The goal of this project is to strengthen my SQL fundamentals and demonstrate my ability to design and query structured data.

## 🎯 Learning Objectives
Through this project, I practiced and learned:

- Designing a relational database schema
- Creating tables with primary & foreign keys
- Performing CRUD operations
- Writing JOINs, GROUP BY, HAVING, subqueries
- Using CTAS (Create Table As Select)
- Understanding real-world library workflows like issue, return, and overdue tracking

## 🛠️ Tech Stack
**Database:** PostgreSQL / SQL  

**Concepts Used:**
- DDL & DML
- Joins (INNER, LEFT)
- Aggregations
- Subqueries
- Stored Procedures (Intro level)
- Date & time functions

## 🗂️ Database Structure
The following Entity Relationship Diagram (ERD) represents the database schema and relationships between tables used in the Library Management System.

![Library Management System ERD](/library_erd.png)

The system includes the following tables:

- **Branch** – Library branch details  
- **Employees** – Staff working in branches  
- **Members** – Registered library members  
- **Books** – Book inventory and status  
- **Issued_Status** – Books issued to members  
- **Return_Status** – Returned books information  

The tables are connected using foreign key relationships to maintain data integrity.

## 🔄 Key Operations Implemented
### ✔️ CRUD Operations
- Insert new books and members  
- Update member details  
- Delete issue records  
- Retrieve records using filters  

### ✔️ Data Analysis Queries
Some example queries include:

- Books issued but not yet returned  
- Members with multiple book issues  
- Total rental income by book category  
- Employees handling the most book issues  
- Members with overdue books  

### ⚙️ Advanced Concepts (Beginner–Intermediate Exposure)
- CTAS to create summary tables  
- Stored procedures for:  
  - Issuing a book  
  - Returning a book and updating status  
  - Overdue calculation using date difference  
  - Branch-level performance reporting  

> ⚠️ Note: These advanced concepts were implemented as part of learning and experimentation.

## 📊 Sample Use Cases Covered
- Track issued vs returned books  
- Identify overdue books (30+ days)  
- Analyze high-demand books  
- Generate branch-wise performance reports  

## 🚀 How to Run the Project
1. Clone the repository:  
   ```bash
   git clone <https://github.com/HimanshuDevgan03/Library_System_Management.git>
Create the database in PostgreSQL
Run table creation scripts
Insert sample data
Execute queries to explore insights
📌 What This Project Shows
Strong SQL fundamentals
Understanding of database design
Ability to translate real-world problems into SQL
Hands-on practice suitable for internship & fresher roles
👤 Author
Himanshu Devgan
B.Tech (Computer Engineering)
Aspiring Data / SQL Analyst
