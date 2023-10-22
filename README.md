# Mini-Project-Student-Management-System

This mini project is a simple Java program that allows users to perform CRUD (Create, Read, Update, Delete) operations on a "Student" table in a MySQL database. It provides a menu-driven interface for interacting with the database, making it easy for users to manage records. Here's a breakdown of the project:

1. Database Setup:
The project assumes you have MySQL installed and running. It begins by creating a new database named "testdb" using SQL.

2. Table Creation:
ithin the "test" database, a table named "student" is created. This table has three columns: sid (an auto-incremented primary key), sname (the name of a person), and snumber ,scity)

3. Menu-Driven Interface:
The core of the project is a menu-driven interface that allows users to choose from the following options:
Create Record:.
Read Records: 
Update Record: 
Delete Record: 
Exit:

4. Exception Handling:
The program includes proper exception handling to catch and handle errors that may occur during database operations, ensuring the program's stability and user-friendliness.

5. Data Persistence:
The data entered into the "student" table is stored in the MySQL database, allowing users to perform CRUD operations persistently.

6. User Interaction:
The program provides a user-friendly command-line interface, making it accessible to users who can interact with the program by choosing options from the menu.

7. Educational Purpose:
This mini project serves as a valuable learning exercise for those who want to understand how to create a Java application that interacts with a database using JDBC. It demonstrates the principles of connecting to a database, executing SQL queries, and handling user input.

8. Customization:
Users can customize the program by modifying the database credentials and SQL queries as needed for their specific database environment and table structure.
