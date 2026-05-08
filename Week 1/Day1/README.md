# Week 1, Day 1 - SQL Practice Queries Assignment

This repository folder contains the solutions to **65 SQL practice queries** spanning multiple difficulty levels and topics.

---

## 📂 Repository Structure

- **schema.sql**  
  Contains the `CREATE TABLE` and `INSERT INTO` statements to construct the required mock environment.

- **queries.sql**  
  Contains the solutions to all 65 questions, organized by category, fully commented, and formatted for readability.

---

## 🗄️ Database Schema Overview

The assignment is based on three interconnected tables:

### 1. Department Table
Stores company departments  
- `department_id` (Primary Key)  
- `name`

### 2. Employee Table
Stores employee records  
- `emp_id` (Primary Key)  
- `name`  
- `age`  
- `salary`  
- `department_id` (Foreign Key → Department)  
- `hire_date`

### 3. Project Table
Stores project information  
- `project_id` (Primary Key)  
- `name`  
- `department_id` (Foreign Key → Department)

---

## 🛠️ Concepts Covered

The `queries.sql` script provides practical examples of the following core SQL concepts:

- **Basic SELECT & WHERE**  
  Filtering data using simple conditions

- **String Matching**  
  Using `LIKE` and wildcard characters

- **Date Functions**  
  Extracting and filtering by dates and years

- **Aggregations**  
  `SUM()`, `AVG()`, `MIN()`, `MAX()`, `COUNT()`

- **Grouping Data**  
  Using `GROUP BY` and `HAVING`

- **Sorting Data**  
  Multi-level sorting with `ORDER BY`

- **Joins**  
  `INNER JOIN`, `LEFT JOIN` for combining tables

- **Subqueries**  
  Independent and correlated subqueries for dynamic calculations

---

## 🚀 How to Use

1. Run `schema.sql` to create tables and insert sample data  
2. Execute queries from `queries.sql`  
3. Explore outputs and understand different SQL concepts

---

