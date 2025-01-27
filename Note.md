# Quick Notes for SI564
SQL and Databases  

## Week 1
Basic Queries describing databases and tables.  
`SHOW DATABASES;` shows all the databases on a server  
`USE database_name;` selects a database to use  
`SHOW TABLES;` shows all the tables in a database  
`DESCRIBE table_name;` shows the columns in a table  
`SELECT * FROM table_name;` shows all the rows in a table  
`SELECT column_name FROM table_name;` shows all the rows in a column

## Week 2
Structured Query Language: `__VERB__ WHAT FROM LOCATION WHERE CONDITION;`
4 basic queries in SQL:
- `SELECT`
  - Get data from the database for display: `SELECT (*) FROM table_name;`
  - Not all queries select data from a database
    - `SELECT NOW()` returns the current time.
    - `SELECT 2+2` returns 4.
  - Rather than query all the data, choose the specific fields of interest.
  - Use `AS` to rename columns or tables: `SELECT column_name AS new_name FROM table_name AS new_table_name;`
  - `DISTINCT` is used to return unique values in a column. `SELECT DISTINCT column_name FROM table_name;`
  - `LIMIT` is used to limit the number of rows returned. `SELECT column_name FROM table_name LIMIT 5;`
      - `LIMIT` should be the last part of the query to avoid limiting the results.
  - `ORDER BY` is used to sort the results. `SELECT column_name FROM table_name ORDER BY column_name ASC/DESC;`
    - We can also order by functions, e.g. `ORDER BY LENGTH(column_name) DESC;` or `ORDER BY RAND();`
- CRUD: Create, Read, Update and Delete
- `WHERE` 

**Everything you do should have a documentation behind it.**
- It has to be clear and communicative.
- It needs to ensure that the next person can understand what you did.
- If you don't have a documentation, create one.

**Primary keys**: unique identifier for each row in a table.
