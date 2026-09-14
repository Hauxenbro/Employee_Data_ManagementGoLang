# Employee_Data_ManagementGoLang
**Problem Statement:**

A list of employees with the following details: ID, Name, Age, and Salary. 
Manager struct that provides the following functionalities:

AddEmployee: Add a new employee to the list.

RemoveEmployee: Remove an employee based on their ID.

GetAverageSalary: Calculate the average salary of all employees.

FindEmployeeByID: Retrieve an employee's details by their ID.

Structures and Function Signatures

**Sample Usage**

manager := Manager{}

manager.AddEmployee(Employee{ID: 1, Name: "Alice", Age: 30, Salary: 70000})

manager.AddEmployee(Employee{ID: 2, Name: "Bob", Age: 25, Salary: 65000})

manager.RemoveEmployee(1)

averageSalary := manager.GetAverageSalary()

employee := manager.FindEmployeeByID(2)
