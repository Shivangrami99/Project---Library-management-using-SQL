 # 📚 Library Management System

- This project is a Library Management System built using SQL, designed to manage books, members, employees, and transactions like issuing and returning books.It simulates a real-world library database and demonstrates how relational databases handle structured data efficiently.

# 🧠 Problem Statement

- Libraries need a structured system to manage:

1) : Book inventory
2) : Member records
3) : Issue & return tracking
4) : Employee and branch operations
- This project solves that by designing a relational database and performing analytical queries.


# Database Design

- The system is built using multiple related tables:

- Books – Stores book details like title, category, price, and availability
- Members – Stores library user information
- Employees – Staff working in branches
- Branch – Library branch details
- Issued_Status – Tracks issued books
- Return_Status – Tracks returned books

 # Tools & Technologies

SQL (PostgreSQL)
Relational Database Design
Joins, Aggregations, Subqueries
CTAS (Create Table As Select)

# 🔍 Key Features & Tasks

> Data Manipulation
Insert, update, and delete records
Manage book inventory and member details

> Data Analysis Queries
Books issued by specific employees
Members issuing multiple books
Books by category
Total rental income by category

> Advanced SQL
Created summary tables using CTAS
Identified overdue books using date calculations
Used JOINs to combine multiple tables

> Business Insights
Branch performance report (revenue, issued, returned)
Active members in last 2 months
Employees handling most transactions

All tasks are implemented using structured SQL queries


library-management-sql/
│
├── 📄 lib_management.sql       # Step 1 — Create all tables & foreign keys
├── 📄 insert_queries.sql       # Step 2 — Insert core data (books, members, employees)
├── 📄 insert_queries2.sql      # Step 3 — Extra inserts + ALTER TABLE changes
├── 📄 TASK.sql                 # Step 4 — 16 business problem queries
└── 📄 README.md                # Project documentation
|
| 
Author : Shivang Rami 😊
