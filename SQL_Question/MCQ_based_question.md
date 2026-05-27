1. Which SQL statement is used to extract data from a database?
A) GET
B) OPEN
C) SELECT
D) EXTRACT

2. Which clause is used to filter records in a SQL query?
A) FILTER BY
B) WHERE
C) HAVING
D) QUERY

3. What is the purpose of the AUTO_INCREMENT attribute in MySQL?
A) To automatically create a database
B) To generate a unique number automatically when a new record is inserted
C) To automatically increment the value of all columns
D) To automatically create a primary key con	straint

4. Which command is used to delete an entire table, including its structure?
A) DELETE FROM table_name;
B) DROP TABLE table_name;
C) TRUNCATE TABLE table_name;
D) REMOVE TABLE table_name;

5. The UPDATE statement in SQL is used to:
A) Update the structure of a table
B) Update data in a database
C) Update the privileges of a user
D) Update the database schema

6. Which of the following is a Data Definition Language (DDL) command?
A) SELECT
B) INSERT
C) CREATE
D) UPDATE

7. What will the following query do? DELETE FROM Employees;
A) Delete the Employees table from the database.
B) Delete the database containing the Employees table.
C) Delete all records from the Employees table but keep its structure.
D) Throw an error because no condition is specified.

8. Which data type would be most suitable for storing a large text like a blog post in MySQL?
A) VARCHAR(255)
B) CHAR(1000)
C) TEXT
D) BLOB

9. What is the default port number for the MySQL server?
A) 8080
B) 1433
C) 3306
D) 5432

10. Which statement is used to add a new column to an existing table?
A) ALTER TABLE table_name ADD column_name;
B) MODIFY TABLE table_name ADD column_name;
C) UPDATE TABLE table_name ADD COLUMN column_name;
D) INSERT COLUMN INTO table_name;

11. What is the difference between the WHERE and HAVING clauses?
A) WHERE is used for rows, HAVING is used for columns.
B) WHERE is used before GROUP BY, HAVING is used after GROUP BY.
C) WHERE can be used with SELECT, HAVING can only be used with DELETE.
D) There is no difference; they are interchangeable.

12. Which operator is used to search for a specified pattern in a column?
A) LIKE
B) SIMILAR TO
C) GET
D) MATCH

13. What will SELECT * FROM Customers ORDER BY Country DESC, CustomerName ASC; do?
A) Sort primarily by CustomerName in ascending order and then by Country in descending order.
B) Sort primarily by Country in descending order and then by CustomerName in ascending order.
C) Sort by Country in ascending order only.
D) Sort by CustomerName in descending order only.

14. Which of the following is the correct syntax to limit the results to 10 records?
A) LIMIT 10
B) TOP 10
C) FIRST 10
D) ROWNUM = 10

15. The BETWEEN operator in SQL is:
A) Inclusive
B) Exclusive
C) Sometimes inclusive, sometimes exclusive
D) Used only with dates

16. What does the % wildcard represent in a LIKE operator pattern?
A) A single character
B) Zero or more characters
C) Exactly one digit
D) A special character

17. Which statement is true about the DISTINCT keyword?
A) It sorts the result set.
B) It is used with the UPDATE statement.
C) It is used to eliminate duplicate rows from the result set.
D) It can only be applied to one column.

18. What is the purpose of the IFNULL() function in MySQL?
A) To return a specified value if the expression is NULL
B) To check if a value is NULL
C) To convert a value to NULL
D) To ignore NULL values in calculations

19. Which query finds all customers whose name starts with 'Br'?
A) SELECT * FROM Customers WHERE CustomerName LIKE 'Br%';
B) SELECT * FROM Customers WHERE CustomerName = 'Br*';
C) SELECT * FROM Customers WHERE CustomerName LIKE '*Br';
D) SELECT * FROM Customers WHERE CustomerName = 'Br';

20. What is the result of SELECT 10 + '5' in MySQL?
A) '105' (string concatenation)
B) 15 (numeric addition)
C) Error
D) NULL

21. What is a Foreign Key?
A) A key that is not unique
B) A key that uniquely identifies a record in another table
C) A field in one table that refers to the PRIMARY KEY in another table
D) A key that is used only for temporary tables

22. Which type of JOIN returns all records when there is a match in either the left or right table?
A) INNER JOIN
B) LEFT JOIN
C) RIGHT JOIN
D) FULL OUTER JOIN

23. You have two tables: Orders and Customers. You want a list of all orders along with customer information, even if the customer information is missing. Which JOIN should you use?
A) INNER JOIN Customers ON Orders.CustomerID = Customers.CustomerID
B) LEFT JOIN Customers ON Orders.CustomerID = Customers.CustomerID
C) RIGHT JOIN Customers ON Orders.CustomerID = Customers.CustomerID
D) CROSS JOIN Customers

24. What is a Cartesian Product?
A) The result of an INNER JOIN
B) The result of a JOIN without a WHERE clause
C) The result of a CROSS JOIN
D) Both B and C

25. The UNION operator is used to:
A) Combine the results of two or more JOINs
B) Combine the result sets of two or more SELECT statements
C) Combine two tables into one
D) Combine two columns into one

26. What is the main difference between UNION and UNION ALL?
A) UNION sorts the data, UNION ALL does not.
B) UNION removes duplicate rows, UNION ALL includes all rows.
C) UNION is faster than UNION ALL.
D) UNION can be used with different numbers of columns.

27. In a self-join, a table is joined with:
A) All other tables in the database
B) A temporary copy of itself
C) A system table
D) A view

28. Which keyword is used to create an alias for a table or column?
A) AS
B) NAME
C) INTO
D) ALIAS

29. Consider two tables: Employees (EmpID, Name, ManagerID)andManagers(MgrID, MgrName). If you want to find employees who are also managers, which query is most efficient?
A) Use a SELF-JOIN on the Employees table.
B) Use a SUBQUERY to find EmpID in ManagerID.
C) Use an INNER JOIN between Employees and Managers on EmpID = MgrID.
D) All of the above are valid approaches.

30. What does NATURAL JOIN do?
A) Joins tables based on all columns with the same name and compatible data types.
B) Joins tables in the most "natural" way possible.
C) Is the same as an INNER JOIN.
D) Joins tables based on primary and foreign keys only.

31. Which function is used to find the average value of a numeric column?
A) AVG()
B) COUNT()
C) MEAN()
D) SUM()

32. What will SELECT COUNT(*) FROM Table; return?
A) The number of distinct rows in the table.
B) The number of non-NULL values in the first column.
C) The total number of rows in the table.
D) The number of columns in the table.

33. The GROUP BY clause is used to:
A) Group rows that have the same values in specified columns.
B) Group similar databases together.
C) Group the results in ascending or descending order.
D) Group tables together for a JOIN.

34. You want to find the department with more than 5 employees. Which query is correct?
A) SELECT Dept, COUNT(EmpID) FROM Employees WHERE COUNT(EmpID) > 5 GROUP BY Dept;
B) SELECT Dept, COUNT(EmpID) FROM Employees GROUP BY Dept HAVING COUNT(EmpID) > 5;
C) SELECT Dept, COUNT(EmpID) FROM Employees GROUP BY Dept WHERE COUNT(EmpID) > 5;
D) SELECT Dept, COUNT(EmpID) FROM Employees HAVING COUNT(EmpID) > 5 GROUP BY Dept;

35. What is the difference between COUNT(column_name) and COUNT(*)?
A) There is no difference.
B) COUNT(column_name) ignores NULL values, while COUNT(*) counts all rows.
C) COUNT(*) ignores NULL values, while COUNT(column_name) counts all rows.
D) COUNT(column_name) is faster than COUNT(*).

36. Which function returns the highest value in a column?
A) MAX()
B) TOP()
C) HIGH()
D) UPPER()

37. What does the GROUP_CONCAT() function do in MySQL?
A) Concatenates multiple rows into a single string for a group.
B) Groups tables together.
C) Concatenates multiple columns into one.
D) It is the same as the CONCAT() function.

38. If a GROUP BY clause is used without an aggregate function, it behaves most like:
A) A WHERE clause
B) An ORDER BY clause
C) The DISTINCT keyword
D) A JOIN

39. Consider a Products table with a Price column. What does SELECT SUM(Price) FROM Products; return if one of the Price values is NULL?
A) NULL
B) 0
C) The sum of all non-NULL prices.
D) An error.

40. Which query finds the second highest salary from an Employees table?
A) SELECT MAX(salary) FROM Employees WHERE salary < (SELECT MAX(salary) FROM Employees);
B) SELECT salary FROM Employees ORDER BY salary DESC LIMIT 1 OFFSET 1;
C) Both A and B
D) Neither A nor B

47. What is a "view" in SQL?
A) A virtual table based on the result-set of a SQL statement
B) The visual layout of a table
C) A copy of a table
D) A stored procedure

48. Which statement is used to remove a view?
A) DELETE VIEW
B) DROP VIEW
C) REMOVE VIEW
D) ALTER VIEW

50. What is the purpose of the EXPLAIN keyword in MySQL?
A) To explain the error in a SQL query
B) To provide information about how MySQL executes a query
C) To explain the structure of a table
D) To comment on a SQL statement
