# SQL Queries
- This repository contains a collection of SQL queries for analyzing data(Basic, Intermediate and Advanced including joins, CTEs, stored procedures, views, index)

## SQL Queries
1. Data Retrieval
Queries to fetch and filter data from a table.

- SELECT: Retrieve data from a table.
- WHERE: Filter data with conditions.
- ORDER BY: Sort the data.

2. Aggregation
Queries for summarizing data with calculations.

- COUNT(): Count the number of records.
- SUM(): Sum values.
- AVG(): Calculate average values.
- GROUP BY: Group data for aggregation.

3. Join
Queries to combine data from multiple tables.

- INNER JOIN: Get matching records from both tables.
- LEFT JOIN: Get all records from the left table.
- RIGHT JOIN: Get all records from the right table, and matching records from the left.
- FULL OUTER JOIN: Get records that have matching values in either the left or the right table.
- CROSS JOIN: Combine each record from the left table with all records from the right table (produces a Cartesian product).
- SELF JOIN: Join a table with itself to compare rows within the same table.

4. Subqueries
Queries within other queries.

- IN: Check if a value exists in a subquery.
- EXISTS: Check if a subquery returns results.

5. Data Modification
Queries to modify data in tables.

- INSERT: Add new records.
- UPDATE: Modify existing records.
- DELETE: Remove records.

6. Stored Procedures

- A Stored Procedure is a precompiled collection of SQL statements stored in the database.
- It helps in automating repetitive tasks, improving performance, and ensuring code reusability.

7. Views

- A View in SQL is a virtual table that is created based on the result of a SQL query.
- It does not store data itself but retrieves data dynamically from the underlying tables.

8. User-Defined Functions (UDFs)

- A User-Defined Function (UDF) is a custom function created by users to perform specific tasks in SQL.
- Unlike stored procedures, UDFs must return a value and cannot modify database data (e.g., INSERT, UPDATE, DELETE).
