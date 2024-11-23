# Assignment Questions and Answers

### 1. State and Explain the components of a DBMS (Database Management System)

A **Database Management System (DBMS)** consists of the following components:

- **Database Engine**: This is the core service for accessing and managing data. It handles operations like querying, updating, and data storage.
- **Database Schema**: The structure that defines how data is organized in the database (e.g., tables, views, indexes).
- **Query Processor**: This component interprets and executes queries written in SQL (Structured Query Language) and translates them into actions.
- **Transaction Management**: It ensures that the database remains consistent and handles operations such as rollback, commit, and isolation of transactions.
- **Data Dictionary**: A repository containing metadata that describes the structure of the database (tables, columns, types, etc.).
- **Database Administrator (DBA)**: A person responsible for managing the database system, including backups, security, and maintenance.

---

### 2. What is a relational database? Give 4 examples.

A **relational database** is a type of database that stores data in tables (also called relations) and enforces relationships between the data through keys. It uses Structured Query Language (SQL) for querying and managing data.

**Examples of relational databases**:
- **MySQL**
- **PostgreSQL**
- **Oracle Database**
- **Microsoft SQL Server**

---

### 3. State and Explain three classifications of SQL

SQL can be classified into the following types:

- **Data Definition Language (DDL)**: DDL commands define the structure of a database, including creating, modifying, and deleting tables, schemas, and relationships. Examples: `CREATE`, `ALTER`, `DROP`.
- **Data Manipulation Language (DML)**: DML commands allow for the manipulation of data in the database, including inserting, updating, and deleting records. Examples: `INSERT`, `UPDATE`, `DELETE`.
- **Data Query Language (DQL)**: DQL commands are used to query data from the database. The primary command is `SELECT`, which retrieves data based on specified conditions.

---

### 4. What is the difference between a Primary Key and a Foreign Key?

- **Primary Key**:
  - A primary key is a column or a set of columns in a table that uniquely identifies each row in the table. 
  - It cannot have NULL values.
  - Example: In a `users` table, the `user_id` can be a primary key.

- **Foreign Key**:
  - A foreign key is a column or set of columns in a table that refers to the primary key of another table.
  - It establishes and enforces a link between the data in two tables.
  - Example: In an `orders` table, the `user_id` column might be a foreign key referring to the `user_id` in the `users` table.

---

### 5. What is an Entity-Relationship Diagram (ERD)?

An **Entity-Relationship Diagram (ERD)** is a visual representation of the entities (tables) in a database and their relationships to each other. It is used in database design to model the structure of the database and the interactions between entities. Components of an ERD include:

- **Entities**: Represented as rectangles, they usually correspond to tables in a database.
- **Attributes**: Represented as ovals, they define the characteristics or properties of the entities.
- **Relationships**: Represented as diamonds, they define how two entities are related to each other.
  
---

### 6. What are the advantages of relational databases?

Advantages of relational databases include:

- **Data Integrity**: The relational model enforces constraints such as primary keys, foreign keys, and unique constraints to ensure data accuracy and consistency.
- **Flexibility**: SQL provides powerful query capabilities for retrieving and manipulating data.
- **Data Security**: Access control mechanisms in relational databases allow for fine-grained permissions, protecting sensitive data.
- **Scalability**: Relational databases can handle large amounts of data and transactions while maintaining performance.
- **Standardization**: SQL is a standardized language that is widely used, making it easier for developers and administrators to work across different systems.

---

### 7. State four types of data types used to store data in tables

Common data types used in relational databases include:

- **INT**: Used for storing integer (whole number) values.
- **VARCHAR**: Used for storing variable-length strings (text).
- **DATE**: Used for storing date values in the format `YYYY-MM-DD`.
- **DECIMAL**: Used for storing exact numeric values, often used for monetary data.

---

### 8. What is the purpose of a database management system (DBMS)?

The primary purpose of a **Database Management System (DBMS)** is to provide an interface for users and applications to interact with data stored in a database. Key purposes include:

- **Data Storage**: Efficiently store large volumes of structured data.
- **Data Retrieval**: Allow users to query the database to retrieve and manipulate data.
- **Data Integrity**: Ensure the accuracy and consistency of data.
- **Data Security**: Protect data from unauthorized access and corruption.
- **Transaction Management**: Handle multiple database transactions and ensure that they are executed in a reliable and isolated manner.
- **Backup and Recovery**: Facilitate database backup and restore operations to prevent data loss.

