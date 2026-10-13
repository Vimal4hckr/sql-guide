# SQL Guide – DBMS and MySQL

Welcome to **SQL Guide**, a collection of study materials designed to help students learn Database Management Systems (DBMS), SQL, and MySQL through presentations and reference documents.

This repository provides learning resources for understanding database concepts, writing SQL queries, managing data, and working with relational databases.

## 📚 Topics Covered

| No. | Topic | Description |
|---|---|---|
| 01 | Fundamentals of DBMS | Database concepts, DBMS architecture, and database fundamentals |
| 02 | SQL with MySQL | SQL syntax, queries, and working with MySQL |
| 03 | DML – Data Manipulation Language | Inserting, updating, deleting, and retrieving data |
| 04 | TCL – Transaction Control Language | Managing transactions using commands such as `COMMIT` and `ROLLBACK` |
| 05 | DCL – Data Control Language | Database permissions and access control |
| 06 | ORDER BY | Sorting query results in ascending or descending order |
| 07 | Foreign Keys | Establishing relationships between tables |
| 08 | SQL Joins | Combining related data from multiple tables |

## 📁 Repository Contents

| File | Description |
|---|---|
| `1_Fundamentals of DBMS.pptx` | DBMS fundamentals presentation |
| `2_SQL with MySQL.pptx` | Introduction to SQL and MySQL |
| `3_DML Language.pptx` | Data Manipulation Language |
| `4_TCL Language.pptx` | Transaction Control Language |
| `5_DCL Language.pptx` | Data Control Language |
| `6_Order_By.pptx` | Sorting query results |
| `7_FOREIGN KEY.pptx` | Foreign key concepts |
| `SQL - Joins.pdf` | SQL joins study material |
| `SQL Study Matrial.pdf` | SQL study material |
| `SQL_Text_Book [Good].pdf` | Additional SQL reference material |

## 🛠️ Technologies and Tools

- **Query Language:** SQL
- **Database Management System:** MySQL
- **Learning Resources:** PowerPoint presentations and PDF documents

## 🚀 Getting Started

### Step 1: Clone the Repository

```bash
git clone https://github.com/Vimal4hckr/sql-guide.git
cd sql-guide
```

### Step 2: Study the Materials

Open the PowerPoint presentations using Microsoft PowerPoint or a compatible presentation application. Open the PDF files using a PDF reader.

### Step 3: Practise SQL Queries

Install MySQL or use an available MySQL learning environment to practise the concepts.

Example:

```sql
CREATE DATABASE college;

USE college;

CREATE TABLE students (
    student_id INT PRIMARY KEY,
    student_name VARCHAR(100),
    department VARCHAR(50)
);

INSERT INTO students
VALUES (1, 'Arun', 'Computer Science');

SELECT * FROM students;

SELECT *
FROM students
ORDER BY student_name ASC;
```

## 🎯 Learning Objectives

- Understand database management systems and relational databases.
- Learn SQL commands and fundamental query syntax.
- Perform data manipulation using SQL.
- Understand transaction management and access control.
- Establish relationships between tables using primary and foreign keys.
- Retrieve information from multiple tables using joins.
- Practise SQL queries using MySQL.

## 💡 Recommended Learning Path

1. Start with DBMS fundamentals.
2. Learn SQL syntax and basic queries.
3. Practise DML commands.
4. Understand TCL and DCL.
5. Study sorting, keys, and table relationships.
6. Learn SQL joins and practise queries using sample databases.

## 🤝 Contributions

Suggestions, corrections, and additional educational resources are welcome. You can fork the repository, create a branch for your changes, and submit a pull request.

## 📄 License and Usage

No repository license has been specified. Please check the applicable terms for individual study materials and obtain permission where necessary before redistributing them.

---

**Maintained by [Vimal4hckr](https://github.com/Vimal4hckr)**
