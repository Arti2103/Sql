# Sql
You are given two tables: Employees and Departments. The Employees table contains information about
employees, including their EmployeeID, Name, DepartmentID, and Salary. The Departments table
contains information about departments, including their DepartmentID and Name.

Write a SQL query to find the average salary of employees in each department, along with the
department name and the number of employees in each department. However, only include
departments where the average salary is higher than the overall average salary across all departments.

Input:-
Employees table
EmployeeID Name DepartmentID Salary
----------- -------------------------------------------------- ------------ ----------
1 John Doe 1 60000.00
2 Jane Smith 1 70000.00
3 Alice Johnson 1 65000.00
4 Bob Brown 1 75000.00
5 Charlie Wilson 1 80000.00
6 Eva Lee 2 70000.00
7 Michael Clark 2 75000.00
8 Sarah Davis 2 80000.00
9 Ryan Harris 2 85000.00
10 Emily White 2 90000.00
11 David Martinez 3 95000.00
12 Jessica Taylor 3 100000.00
13 William Rodriguez 3 105000.00

department table:-
DepartmentID Name
------------ --------------------------------------------------

1 Marketing
2 Research
3 Development

OUTPUT:-
DepartmentName AverageSalary NumberOfEmployees
-------------------------------------------------- -----------------------------------
Development 100000.000000 
