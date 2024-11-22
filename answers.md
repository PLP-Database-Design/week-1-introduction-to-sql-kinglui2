1. Components of a DBMS (Database Management System)
    -A DBMS consists of the following components:

    -Database Engine: It is the core service for accessing and processing the database. It handles tasks such as querying, storing, and updating data.

    -Database Schema: The schema defines the structure of the database, including tables, views, and relationships between entities.

    -Query Processor: This component interprets and executes SQL queries. It translates high-level commands into low-level operations.

    -Data Dictionary: It stores metadata, such as definitions of tables, columns, data types, and constraints, ensuring data consistency and integrity.

    -Transaction Management: Ensures that database transactions are processed reliably and adhere to the ACID properties (Atomicity, Consistency, Isolation, Durability).

    -Security and Authorization: Manages user access controls, defining who can read, write, or modify data in the database.

    -Backup and Recovery: Ensures data integrity and recovery after failures by regularly backing up data and providing mechanisms to restore it.

2. What is a Relational Database? Give 4 Examples.
    -A relational database is a type of database that stores data in tables (also known as relations) consisting of rows and columns. Data in relational databases are organized in a way that relationships between the data items are represented using keys (primary and foreign).

    Examples of relational databases:

    -MySQL
    -PostgreSQL
    -Oracle Database
    -Microsoft SQL Server

3. Three Classifications of SQL
    -SQL can be classified into three categories:

    1.Data Definition Language (DDL): Defines and manages database structure. Examples include:

    -CREATE (to create tables or databases)
    -ALTER (to modify database objects)
    -DROP (to delete tables or databases)

    2.Data Manipulation Language (DML): Deals with manipulating data within the database. Examples include:

    -SELECT (to query data)
    -INSERT (to add new records)
    -UPDATE (to modify existing data)
    -DELETE (to remove data)

    3.Data Control Language (DCL): Controls access to the data within the database. Examples include:

    -GRANT (to provide access privileges)
    -REVOKE (to remove access privileges)

4. Difference Between Primary Key and Foreign Key
    1.Primary Key: A primary key is a unique identifier for each record in a database table. It ensures that no two rows can have the same value for the primary key field.
    Example: In a "Customers" table, the CustomerID could be a primary key.

    2.Foreign Key: A foreign key is a field in one table that links to the primary key in another table. It is used to establish and enforce relationships between the tables.
    Example: In an "Orders" table, the CustomerID could be a foreign key referencing the CustomerID in the "Customers" table.

5. What is an Entity-Relationship Diagram (ERD)?
    -An Entity-Relationship Diagram (ERD) is a graphical representation of entities and their relationships in a database. It uses symbols to depict entities (tables) and relationships (associations between tables). An ERD helps in designing a database schema by clearly defining the structure and relationships between different data elements.

6. Advantages of Relational Databases
    -Data Integrity: Enforces rules like constraints and relationships to ensure data consistency and accuracy.
    -Flexibility: Easy to update, delete, and modify data using SQL.
    -Data Redundancy Reduction: Uses normalization to eliminate duplicate data, reducing storage requirements.
    -Scalability: Can handle large amounts of data efficiently, supporting high-volume transactions.
    -Security: Provides strong security features like access control, ensuring that only authorized users can access or modify data.

7. Four Types of Data Types Used to Store Data in Tables
    -INT: Stores integer numbers (e.g., 1, 50, -10).
    -VARCHAR: Stores variable-length strings (e.g., names, addresses).
    -DATE: Stores date values (e.g., 2024-11-22).
    -DECIMAL: Stores numbers with decimal points for precision (e.g., 10.99, 100.50).

8. Purpose of a Database Management System (DBMS)
    -The primary purpose of a DBMS is to provide an efficient, secure, and structured way to store, manage, and retrieve data. It helps in:

    -Data organization: Efficiently organizes large volumes of data.
    -Data retrieval: Makes data querying faster and more flexible.
    -Data integrity: Ensures consistency, accuracy, and validity of data.
    -Concurrency control: Manages multiple users accessing the database simultaneously.
    -Backup and recovery: Protects against data loss by providing mechanisms to back up and restore data.