Employee Database: A mystery in two parts

This project utilizes data engineering and data analysis to build a SQL database of employees of a fictional corporation called Pewlett Hackard during the 1980s and 1990s. Six CSV files containing the employee data were used.

Contents:
1. employee_ERD.png: An image file of the ERD
2. employee_schema.sql: A .sql file of the table schemata
3. employee_query.sql: A .sql file of the queries
4. employee.ipynb: A Jupyter Notebook of the bonus analysis
5. salaryrange.png: A visualization of salary ranges
6. averagesalary.png: A visualization of average salary per title
7. data folder containing the CSV files used

Data Engineering:
The CSVs were inspected and the QuickDBD was used to sketch out an ERD of the tables. The information from the ERD was used to create a table schema for each of the six CSV files. The SQL tables were created and each CSV file was imported into the corresponding SQL table.

Data Analysis:
1. List the following details of each employee: employee number, last name, first name, sex and salary
2. List first name, last name, and hire date for employees who were hired in 1986
3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name
4. List the department of each employee with the following information: employee number, last name, first name, and department name
5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B"
6. List all employees in the Sales department, including their employee number, last name, first name, and department name
7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name
8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name

Bonus Analysis: A visualization of the data was generated.
1. Import the SQL database into Pandas
2. Create a histogram to visualize the most common salary ranges for employees
3. Create a bar chart of average salary by title
