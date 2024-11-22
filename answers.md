# Assignment Questions and Answers

## 1. State and Explain the components of a DBMS (Database Management System)
A DBMS consists of the following components:
1. **Database Engine**: Responsible for storing, retrieving, and updating data in the database.
2. **Database Schema**: Defines the logical structure of the database, including tables, columns, and relationships.
3. **Query Processor**: Interprets and executes database queries using SQL or other query languages.
4. **Transaction Manager**: Ensures data consistency and integrity during concurrent transactions.
5. **Data Dictionary**: Stores metadata about the database, such as schema definitions and constraints.
6. **User Interface**: Allows users to interact with the database through GUI or command-line tools.
7. **Security and Authorization Manager**: Handles user authentication and access control.
8. **Backup and Recovery Manager**: Ensures data safety by managing backups and recovery processes.

## 2. What is a relational database? Give 4 examples.
A relational database is a type of database that stores data in structured tables with rows and columns, where relationships between tables are defined by keys. It uses SQL for data manipulation and retrieval.
Examples:
1. MySQL
2. PostgreSQL
3. Oracle Database
4. Microsoft SQL Server

## 3. State and Explain three classifications of SQL
1. **Data Definition Language (DDL)**: Commands that define or modify database structures, such as `CREATE`, `ALTER`, and `DROP`.
2. **Data Manipulation Language (DML)**: Commands used to manipulate data within tables, such as `SELECT`, `INSERT`, `UPDATE`, and `DELETE`.
3. **Data Control Language (DCL)**: Commands that control user access to the database, such as `GRANT` and `REVOKE`.

## 4. What is the difference between a Primary Key and a Foreign Key?
- **Primary Key**: A unique identifier for each record in a table. It ensures that no duplicate or null values exist in the key column.
- **Foreign Key**: A column or set of columns in a table that references the primary key in another table. It is used to establish and enforce relationships between tables.

## 5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the entities in a database, their attributes, and the relationships between them. It is used during database design to model data structure and relationships clearly.

## 6. What are the advantages of relational databases?
1. **Data Integrity**: Ensures accuracy and consistency through constraints like primary keys and foreign keys.
2. **Flexibility**: Allows data to be added, updated, or queried in multiple ways.
3. **Scalability**: Supports large datasets and complex queries.
4. **Standardization**: Uses SQL, a widely accepted query language.
5. **Data Security**: Provides robust mechanisms for user authentication and authorization.

## 7. State four types of data types used to store data in tables
1. **Integer**: Stores whole numbers (e.g., `INT` in SQL).
2. **String**: Stores text data (e.g., `VARCHAR`, `CHAR`).
3. **Date/Time**: Stores date and time values (e.g., `DATE`, `TIMESTAMP`).
4. **Float/Decimal**: Stores decimal or floating-point numbers (e.g., `FLOAT`, `DECIMAL`).

## 8. What is the purpose of a database management system (DBMS)?
The purpose of a DBMS is to provide an efficient and secure environment for storing, managing, and retrieving data. It simplifies database administration, ensures data integrity, supports concurrent access, and provides tools for data backup and recovery.
