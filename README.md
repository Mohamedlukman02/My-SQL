# MySQL Practice Repository

This repository contains my MySQL and SQL practice programs covering database creation, table operations, queries, constraints, joins, normalization, subqueries, window functions, stored procedures, and triggers.

## 📚 Topics Covered

### 01. Database and Table Creation

**File:**
`01_MySQL_SchoolDB_Create_Table_Insert_Select_Drop.sql`

Concepts:
- CREATE DATABASE
- USE DATABASE
- CREATE TABLE
- INSERT INTO
- SELECT
- DROP DATABASE

Practice:
- Created `schoolDB`
- Created students table
- Inserted student records
- Retrieved data

---

### 02. SQL Constraints

**File:**
`02_MySQL_CompanyDB_Employee_Constraints.sql`

Concepts:
- PRIMARY KEY
- NOT NULL
- UNIQUE
- DEFAULT
- CHECK Constraint

Practice:
- Created employee database
- Applied table constraints
- Tested duplicate email validation

---

### 03. ALTER, UPDATE and DELETE Operations

**File:**
`03_MySQL_Product_Table_Alter_Update_Delete.sql`

Concepts:
- ALTER TABLE
- ADD COLUMN
- RENAME COLUMN
- UPDATE
- DELETE

Practice:
- Modified product table structure
- Updated product stock
- Deleted records

---

### 04. Filtering and Sorting Data

**File:**
`04_MySQL_Orders_Table_Filtering_Sorting.sql`

Concepts:
- WHERE
- BETWEEN
- LIKE
- ORDER BY
- DESC

Practice:
- Filtered orders
- Searched products
- Sorted records

---

### 05. Aggregate Functions and Grouping

**File:**
`05_MySQL_Order_Aggregate_Functions_Grouping.sql`

Concepts:
- COUNT()
- SUM()
- AVG()
- MAX()
- MIN()
- GROUP BY

Practice:
- Calculated total orders
- Found average price
- Generated sales summary

---

### 06. Date Functions

**File:**
`06_MySQL_Events_Date_Functions.sql`

Concepts:
- NOW()
- DATE_FORMAT()
- YEAR()
- MONTH()
- CONCAT()

Practice:
- Managed event dates
- Formatted date values
- Extracted date information

---

### 07. Joins and Normalization

**File:**
`07_MySQL_Joins_Normalization_2NF_3NF.sql`

Concepts:
- INNER JOIN
- LEFT JOIN
- Foreign Key
- 2NF
- 3NF

Practice:
- Connected customers and orders tables
- Learned database normalization

---

### 08. Subqueries and EXISTS

**File:**
`08_MySQL_Subqueries_Correlated_Subquery_EXISTS.sql`

Concepts:
- Subquery
- Nested Query
- EXISTS
- IN Operator

Practice:
- Compared salary data
- Checked product existence

---

### 09. Window Functions and CTE

**File:**
`09_MySQL_Window_Functions_CTE_Sales_Analysis.sql`

Concepts:
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- SUM() OVER()
- CTE

Practice:
- Ranked sales data
- Calculated running totals
- Filtered above-average sales

---

### 10. Stored Procedures and Triggers

**File:**
`10_MySQL_Stored_Procedures_Triggers.sql`

Concepts:
- Stored Procedures
- DELIMITER
- CALL
- Triggers
- SIGNAL SQLSTATE

Practice:
- Inserted employees using procedures
- Automated stock updates
- Controlled delete operations

---

### 11. Advanced Subqueries

**File:**
`11_MySQL_Advanced_Subqueries_Correlated_Queries.sql`

Concepts:
- Correlated Subquery
- Aggregate Subquery
- EXISTS
- Self Reference Query

Practice:
- Department salary comparison
- Customer order analysis
- Manager salary comparison

---

## 🛠 Technologies Used

- MySQL
- SQL
- MySQL Workbench

## 📂 Repository Structure

```
MySQL-Practice/
│
├── 01_MySQL_SchoolDB_Create_Table_Insert_Select_Drop.sql
├── 02_MySQL_CompanyDB_Employee_Constraints.sql
├── 03_MySQL_Product_Table_Alter_Update_Delete.sql
├── 04_MySQL_Orders_Table_Filtering_Sorting.sql
├── 05_MySQL_Order_Aggregate_Functions_Grouping.sql
├── 06_MySQL_Events_Date_Functions.sql
├── 07_MySQL_Joins_Normalization_2NF_3NF.sql
├── 08_MySQL_Subqueries_Correlated_Subquery_EXISTS.sql
├── 09_MySQL_Window_Functions_CTE_Sales_Analysis.sql
├── 10_MySQL_Stored_Procedures_Triggers.sql
├── 11_MySQL_Advanced_Subqueries_Correlated_Queries.sql
└── README.md
```

## 👨‍💻 Author

**Mohamed Lukman**

B.Tech Information Technology Student  
Full Stack Web Developer
