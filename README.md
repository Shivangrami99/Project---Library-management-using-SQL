- # 📚 Library Management System

- This project is a Library Management System built using SQL, designed to manage books, members, employees, and transactions like issuing and returning books.It simulates a real-world library database and demonstrates how relational databases handle structured data efficiently.

-# 🧠 Problem Statement

- Libraries need a structured system to manage:

1) : Book inventory
2) : Member records
3) : Issue & return tracking
4) : Employee and branch operations
- This project solves that by designing a relational database and performing analytical queries.


-# Database Design

- The system is built using multiple related tables:

- Books – Stores book details like title, category, price, and availability
- Members – Stores library user information
- Employees – Staff working in branches
- Branch – Library branch details
- Issued_Status – Tracks issued books
- Return_Status – Tracks returned books

- # Tools & Technologies

SQL (PostgreSQL)
Relational Database Design
Joins, Aggregations, Subqueries
CTAS (Create Table As Select)

-# 🔍 Key Features & Tasks

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

- # Project Structure : 
│
|-- 📂 data/
│   |-- books.csv
│   |-- members.csv
│   |-- employees.csv
│   |-- branch.csv
│   |-- issued_status.csv
│   |-- return_status.csv
│
|-- 📂 sql/
│   |-- schema.sql              # Table creation + constraints
│   |-- insert_data.sql         # Data insertion queries
│   |-- update_queries.sql      # Updates & modifications
│   |-- analysis_queries.sql    # All business queries / tasks
|   |-- tasks.sql               # Real-world business problem solving 
│
|-- 📂 docs/
│   |-- ERD.png / ERD.pgerd    # Database design diagram
|
| 
Author : Shivang Rami 😊
