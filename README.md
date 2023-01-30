 # Databases and SQL for Data Science with Python

## 📄 Summary 

Working knowledge of SQL (or Structured Query Language) is a must for data professionals like Data Scientists, Data Analysts and Data Engineers. Much of the world's data resides in databases. SQL is a powerful language used for communicating with and extracting data from databases.

The purpose of this course is to introduce relational database concepts and to learn and apply foundational knowledge of the SQL language. It is also intended to provide a foundation to performing SQL access in a data science environment.  

## 📑 Main Topics

- [Accessing Databases using Python](https://github.com/PramodRawat157/SQL-For-Data-Science-IBM)
  - How to Access Databases Using Python
  - Writing Code using DB-API
  - Connecting to a Database Instance
  - Creating Tables, Inserting, and Querying Data
  - SQL Magic
  - Analysing Data with Python
- [Assignment](https://github.com/PramodRawat157/SQL-For-Data-Science-IBM)
  - Working with Real World Datasets
  - Getting Table and Column Details
  - Loading Data
- [Bonus Module: Advanced SQL for Data Engineering](https://github.com/PramodRawat157/SQL-For-Data-Science-IBM)
  - Views, Stored Procedures, and Transactions
    - Using Views
    - Stored Procedures
    - ACID Transactions
    - Committing and Rolling Back a Transaction
  - JOIN Statements
    - Join Overview
    - Inner Join
    - Outer Joins

## 🔑 Key Skills Learned 

- Access a database from a language like Python by using the appropriate API. Examples include ibm_db API for IBM DB2, psycopg2 for ProstgreSQL, and dblib API for SQL Server.

- DB-API is Python's standard API for accessing relational databases. It allows you to write a single program that works with multiple kinds of relational databases instead of writing a separate program for each one.

- The DB_API  connect constructor creates a connection to the database and returns a Connection Object, which is then used by the various connection methods.

## The connection methods are:

- The cursor() method, which returns a new cursor object using the connection.
- The commit() method, which is used to commit any pending transaction to the database.
- The rollback() method, which causes the database to roll-back to the start of any pending transaction.
- The close() method, which is used to close a database connection. 

- Use SQL Magic commands to execute queries more easily from Jupyter Notebooks. 
- Magic commands have the general format %sql select * from tablename.
- Cell magics start with a double %% (percent) sign and apply to the entire cell.
- Line magics start with a single % (percent) sign and apply to a particular line in a cell.
- Analysing data within a database APIs using SQL and Python
- Creating relational databases on Cloud and working with tables
- Comparing and contrasting DDL to DML
- Writing SQL statements including SELECT, INSERT, UPDATE, and DELETE
- Generating joins to query data from multiple tables


