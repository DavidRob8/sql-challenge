This module was completed using PostgreSQL with pgAdmin 4. 

We are given 6 csv files with data from a fictional company for individuals employed during the 1980s and 1990s (see "data" folder). 

I designed 6 tables based off the csv files, and imported the files into the respective tables (see "schema" SQL file). Once these tables were completed and filled with the data from the imported files, I was able to perform the following queries (see "data_analysis" SQL file) to find out more information about the company structure and the employees in general:

  1 - List the employee number, last name, first name, sex, and salary of each employee.
  
  2 - List the first name, last name, and hire date for the employees who were hired in 1986.
  
  3 - List the manager of each department along with their department number, department name, employee number, last name, and first name.
  
  4 - List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
  
  5 - List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
  
  6 - List each employee in the Sales department, including their employee number, last name, and first name.
  
  7 - List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
  
  8 - List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

I also created an ERD (entity relationship diagram), to display the different tables and their keys to see how all the tables are connected with the use of primary and foreign keys (see "Module 7 ERD" PNG file). 
