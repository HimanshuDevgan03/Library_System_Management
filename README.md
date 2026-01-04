📚 Library Management System (SQL Project)

A SQL-based Library Management System focused on relational database design, CRUD operations, and analytical queries using a real-world library use case.

🎯 Features

Relational database schema with multiple linked tables

Book issue & return tracking

CRUD operations on library data

Analytical queries for insights (overdue books, rentals, performance)

Summary tables using CTAS

Basic stored procedures for issuing and returning books

🛠️ Tech Stack

Database: PostgreSQL / SQL

Concepts:

DDL & DML

Joins (INNER, LEFT)

GROUP BY, HAVING

Subqueries

CTAS (Create Table As Select)

Stored Procedures (intro level)

Date & time functions

🗂️ Database Structure

The Entity Relationship Diagram (ERD) below represents the schema and relationships between tables in the system.

![Library Management System ERD](/library_erd.png)

Tables Included

branch – Library branch details

employees – Staff working in branches

members – Registered members

books – Book inventory and availability

issued_status – Issued book records

return_status – Returned book records

All tables are connected using primary and foreign keys to maintain data integrity.

🔄 Key Operations
CRUD Operations

Insert new books and members

Update member and book details

Delete issued records

Retrieve filtered data

Data Analysis Queries

Books issued but not returned

Members with multiple book issues

Total rental income by category

Employees processing the most issues

Members with overdue books

⚙️ Advanced Concepts

CTAS for summary and reporting tables

Stored procedures for:

Issuing a book

Returning a book and updating status

Overdue calculation using date difference

Branch-wise performance reporting

📁 Project Structure

SQL scripts for table creation

SQL queries for analysis and reporting

ERD image for database visualization

🚀 How to Run
git clone <your-repo-link>


Create the database in PostgreSQL

Run table creation scripts

Insert sample data

Execute queries to explore insights

📌 What This Project Demonstrates

Strong SQL fundamentals

Understanding of relational database design

Ability to solve real-world problems using SQL

Practical experience suitable for internship & fresher roles

👤 Author
Himanshu Devgan
B.Tech (Computer Engineering)
Aspiring Data / SQL Analyst


