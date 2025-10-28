# AGENDA:
<img width="423" height="629" alt="image" src="https://github.com/user-attachments/assets/bc59d461-dd3c-46f1-92ba-ab778dba6fde" />

# JOINS:
A JOIN in SQL is a clause that retrieves data by linking rows from multiple tables based on a common column.
# We using these two tables:
<img width="882" height="852" alt="Screenshot 2025-10-24 223057" src="https://github.com/user-attachments/assets/4b30b2c9-6abb-4d90-9187-31cd4783472b" />

# INNER JOIN:
Returns only the rows that have matching values in both tables.
<img width="1069" height="644" alt="Screenshot 2025-10-24 182039" src="https://github.com/user-attachments/assets/d4144c2c-d259-40b7-ba6d-1dc1d77333cb" />
# LEFT JOIN:
Returns all rows from the left table and matching rows from the right table. If there’s no match, it shows NULL for the right table columns.
<img width="935" height="688" alt="Screenshot 2025-10-24 182125" src="https://github.com/user-attachments/assets/3d55915b-5e3a-49a9-b6a6-f9633abd9fb9" />
# RIGHT JOIN:
Returns all rows from the right table and matching rows from the left table. If there’s no match, it shows NULL for the left table columns.
<img width="974" height="686" alt="Screenshot 2025-10-24 182159" src="https://github.com/user-attachments/assets/a22c0210-2b77-44a8-a924-dadfbcaa5d89" />
# FULL JOIN:
Returns all rows from both tables. Rows without a match in the other table will show NULL.
<img width="857" height="657" alt="Screenshot 2025-10-24 182237" src="https://github.com/user-attachments/assets/532cc4a5-7342-4bd9-9999-a53fac0296c9" />
# CROSS JOIN:
Returns all possible combinations of rows from both tables (Cartesian product).
<img width="987" height="864" alt="Screenshot 2025-10-24 182926" src="https://github.com/user-attachments/assets/8b17ad76-f6b2-4cfb-8aa7-39f05eb8e621" />
# ANTI JOIN:
An ANTI JOIN returns rows that do not have matching records in the other table.
# FULL ANTI JOIN 
<img width="1129" height="900" alt="image" src="https://github.com/user-attachments/assets/6fd41091-223f-4d1c-84bf-56701d04dc8e" />

# Set operators
Set operators in SQL are used to combine the results of two or more SELECT queries.

           * UNION           Combines result from both queries and remove duplicates.
           * UNION ALL       Combines result from both queries and it include duplicates.
           * INTERSECT       Returns only the common value from both queries.
           * EXCEPT/MINUS    Returns row from the first query that are not in the second query.
<img width="783" height="421" alt="Screenshot 2025-10-28 161336" src="https://github.com/user-attachments/assets/2892cbf3-b5c2-4e52-9c01-b263e168a624" />

<img width="1208" height="871" alt="Screenshot 2025-10-28 161001" src="https://github.com/user-attachments/assets/d400bb1d-7bcf-4a5c-b180-3b66284c0b72" />
<img width="351" height="208" alt="Screenshot 2025-10-28 161127" src="https://github.com/user-attachments/assets/0a8b31ed-a486-495f-b6ac-6b699c6f3533" />

# SQL Operator:
An SQL operator is a symbol or keyword used to perform operations on data in SQL queries. Operators are used in conditions, calculations, and logical expressions to filter, compare, or manipulate data.
# Arithmetic Operators:
Used for mathematical calculations like Addition,Subtraction,Multiplication and Division .
<img width="992" height="735" alt="Screenshot 2025-10-24 185346" src="https://github.com/user-attachments/assets/0626846b-5b91-432d-b43b-3d1a39c858f4" />

# Comparison Operators:
Used to compare values in conditions.
* =	Equal to	WHERE Salary = 50000
* != or <>	Not equal to	WHERE Salary <> 50000
* >	Greater than	WHERE Salary > 50000
* <	Less than	WHERE Salary < 50000
* >=	Greater than or equal to	WHERE Salary >= 50000
* <=	Less than or equal to	WHERE Salary <= 50000
<img width="750" height="571" alt="Screenshot 2025-10-24 190128" src="https://github.com/user-attachments/assets/c6704ba3-202e-4e78-ab8a-7310593ad7d2" />
<img width="781" height="590" alt="Screenshot 2025-10-24 190111" src="https://github.com/user-attachments/assets/ecb6e478-453f-4cfa-9008-a1747fcb419c" />
<img width="851" height="588" alt="Screenshot 2025-10-24 185857" src="https://github.com/user-attachments/assets/18202d8b-ee28-43ee-8287-63fe9d2362e1" />

# Logical Operator:
Used to combine multiple conditions.
# AND
Both conditions must be true	WHERE DeptID = 101 AND Salary > 50000
<img width="970" height="624" alt="Screenshot 2025-10-24 190722" src="https://github.com/user-attachments/assets/27a11a0a-e1df-4f8c-af6f-263bb149b820" />
# OR
Either condition can be true	WHERE DeptID = 101 OR Salary > 50000
<img width="923" height="616" alt="Screenshot 2025-10-24 190743" src="https://github.com/user-attachments/assets/3ce37dca-ad8a-4e93-991f-9946a23361d8" />
# NOT
Negates the condition	WHERE NOT DeptID = 101
<img width="957" height="633" alt="Screenshot 2025-10-24 190833" src="https://github.com/user-attachments/assets/85f18419-cde9-4abc-8234-6c19dca601ac" />
# CONCAT
<img width="900" height="658" alt="Screenshot 2025-10-24 223507" src="https://github.com/user-attachments/assets/b5907c21-4637-4f9b-ae1b-dd9a728651d3" />

# Procedures:
A Stored Procedure in SQL is a precompiled group of SQL statements (like SELECT, INSERT, UPDATE, etc.) that are stored in the database and can be executed whenever needed.It helps improve performance, reusability, security, and modularity in database operations.
# Create prcedure:
Used to create a new stored procedure for the first time.
<img width="930" height="695" alt="Screenshot 2025-10-28 105953" src="https://github.com/user-attachments/assets/6a93387b-7957-4e5a-a960-97b963058c82" />

# ALTER PROCEDURE:
Used to modify or update an existing stored procedure (instead of dropping and recreating it).
<img width="996" height="703" alt="Screenshot 2025-10-28 110243" src="https://github.com/user-attachments/assets/64aa1741-fd11-4df1-a257-db427e037aec" />

# DROP PROCEDURE:
Used to delete (remove) an existing stored procedure permanently.
<img width="1001" height="671" alt="Screenshot 2025-10-28 110345" src="https://github.com/user-attachments/assets/6294021b-469f-49da-9f5b-e4caca7add27" />

# EXECUTE Procedure:
Used to run (or call) a stored procedure.
<img width="996" height="703" alt="Screenshot 2025-10-28 110243" src="https://github.com/user-attachments/assets/892b1b09-f3f2-49e9-b3fc-ab65e5da3e3f" />

# Subquery:
A subquery is a query inside another query — it can be in the SELECT, FROM, or WHERE clause.
<img width="1255" height="883" alt="Screenshot 2025-10-27 174412" src="https://github.com/user-attachments/assets/fdc66708-51bc-4e93-a6cb-63b099ec51cb" />
# CTE:
A CTE is like a named temporary result set that exists only for the duration of a single query.It makes queries cleaner, reusable, and easier to read compared to subqueries.
<img width="849" height="659" alt="Screenshot 2025-10-27 225015" src="https://github.com/user-attachments/assets/513a4cc9-0237-4280-8504-af268485a6c8" />
<img width="1191" height="629" alt="Screenshot 2025-10-27 230303" src="https://github.com/user-attachments/assets/1eb19e31-65cb-48a4-84b1-7e91d76df413" />

# Views:
A View is a virtual table that is based on the result of an SQL query.It doesn’t store data physically, but instead stores a query that pulls data from one or more tables.So, when you query a view, SQL runs the query behind the scenes and shows you the result like a table.
# Create view:
The CREATE VIEW command is used to create a virtual table based on the result of a SQL query.
<img width="904" height="598" alt="Screenshot 2025-10-27 222957" src="https://github.com/user-attachments/assets/1d026382-5a75-4b84-87ed-46de2259f5ca" />

# DROP VIEW:
Used to delete a view permanently from the database.
<img width="910" height="646" alt="Screenshot 2025-10-27 230458" src="https://github.com/user-attachments/assets/cc4f5f44-dfc6-4de9-974a-f15235c4d53c" />

# Normalization:
Normalization is the process of organizing data in a database to Reduce redundancy (duplicate data).Improve data integrity.Make updates, inserts, and deletes efficient
It divides a large table into smaller related tables and links them using foreign keys.

| StudentID | StudentName | Course       | Instructor    | InstructorPhone        |
| --------- | ----------- | ------------ | ------------- | ---------------------- |
| 1         | Ravi        | DBMS, Python | Anitha, Kumar | 9876543210, 9876501234 |
| 2         | Meena       | Java         | Kumar         | 9876501234             |
| 3         | Arjun       | DBMS, Java   | Anitha, Kumar | 9876543210, 9876501234 |

# 1NF:
All attributes must have atomic (single) values — no repeating or multivalued fields.
| StudentID | StudentName | Course | Instructor | InstructorPhone |
| --------- | ----------- | ------ | ---------- | --------------- |
| 1         | Ravi        | DBMS   | Anitha     | 9876543210      |
| 1         | Ravi        | Python | Kumar      | 9876501234      |
| 2         | Meena       | Java   | Kumar      | 9876501234      |
| 3         | Arjun       | DBMS   | Anitha     | 9876543210      |
| 3         | Arjun       | Java   | Kumar      | 9876501234      |
# 2NF:

* Table must be in 1NF
* All non-key attributes must depend on the entire primary key, not part of it.
  
| StudentID | StudentName | Course |
| --------- | ----------- | ------ |
| 1         | Ravi        | DBMS   |
| 1         | Ravi        | Python |
| 2         | Meena       | Java   |
| 3         | Arjun       | DBMS   |
| 3         | Arjun       | Java   |

| Course | Instructor | InstructorPhone |
| ------ | ---------- | --------------- |
| DBMS   | Anitha     | 9876543210      |
| Python | Kumar      | 9876501234      |
| Java   | Kumar      | 9876501234      |

# 3NF:

* Table must be in 2NF
*  No transitive dependency (non-key depends on another non-key)
| StudentID | StudentName | Course |
| --------- | ----------- | ------ |
| 1         | Ravi        | DBMS   |
| 1         | Ravi        | Python |
| 2         | Meena       | Java   |
| 3         | Arjun       | DBMS   |
| 3         | Arjun       | Java   |

| Course | Instructor |
| ------ | ---------- |
| DBMS   | Anitha     |
| Python | Kumar      |
| Java   | Kumar      |

| Instructor | InstructorPhone |
| ---------- | --------------- |
| Anitha     | 9876543210      |
| Kumar      | 9876501234      |
