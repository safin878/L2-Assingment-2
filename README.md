🎓 Bonus Section (উত্তর বাংলায়)

1️⃣ What is PostgreSQL?

PostgreSQL is an open-source relational database management system (RDBMS), which is ACID compliant. It is used to store, query, update, delete, and create relationships between data.

2️⃣ What is the purpose of a database schema in PostgreSQL?

A schema is a logical grouping that contains tables, views, functions, etc. It helps keep data organized and allows multiple users to work in different environments, i.e. it ensures isolation.

3️⃣ Explain the Primary Key and Foreign Key concepts in PostgreSQL.


Primary Key: A unique identifier that uniquely identifies each record in a table. It can never be null or duplicated.

Foreign Key: This is a column that refers to the Primary Key of another table, creating a relationship between the data.

4️⃣ What is the difference between the VARCHAR and CHAR data types?

Aspect VARCHAR CHAR

Length Variable Fixed

Space usage Takes up space as needed Always takes up a fixed amount of space

Performance Generally fast and efficient Slightly slower on large data

VARCHAR is more commonly used because it saves space.

5️⃣ Explain the purpose of the WHERE clause in a SELECT statement.

The WHERE clause is used to filter data according to specific conditions.

📌 Example:

SQL

SELECT * FROM species

WHERE conservation_status = 'Endangered';

Here only those records whose conservation_status is "Endangered" will be displayed.
