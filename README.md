# SQLemployeePractice

The provided code is good practice because it follows standard conventions and best practices for SQL development.

Overview of the code's function:

Create the database:

The code starts by creating a new database called "AdventureWorks". Creating a separate database for each project or application helps with organization and isolation of data.
Use the AdventureWorks database:

This statement switches the database context to "AdventureWorks", indicating that all subsequent queries and operations will be performed within this database.
Create the Employees table:

The code creates a table named "Employees" with various columns to store employee-related information. The column names and data types are appropriately chosen to accurately represent the data being stored. Naming conventions and choosing the correct data types improve clarity and data integrity.
Import data from the CSV file into the Employees table:

The BULK INSERT statement is used to import data from the CSV file into the "Employees" table. It specifies the file path, file format, and delimiters. This allows you to efficiently load large amounts of data into the table.
Query 1: Retrieve all employees' salaries:

This query retrieves specific columns (EmployeeID, JobTitle, SalariedFlag, CurrentFlag) from the "Employees" table. It provides a general overview of the employees' salaries and employment status.
Query 2: Retrieve all employees with a salary greater than $50,000:

This query applies filtering conditions to retrieve only the employees with a salary greater than $50,000. It demonstrates how to use the WHERE clause to filter data based on specific criteria.
Query 3: Retrieve all employees hired after a specific date:

This query retrieves employees who were hired after January 1, 2010. It showcases how to use the WHERE clause with date comparisons to fetch data based on a specific timeframe.
