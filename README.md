# mini-payroll-system

A simple console-based Java application to manage employee payroll for small businesses.

## Overview

The Mini Payroll System is a Java-based application designed to help small businesses efficiently manage employee payroll.  
It allows users to **add, search, update, delete, and list employee records**, as well as **compute salaries** for both full-time and part-time employees. Salary computations are based on daily rates for full-time workers and hourly rates for part-time workers.

This system simplifies the process of organizing employee data and payroll information, offering a fast, accurate, and user-friendly tool for managing employee data.

## Users can

- Add Employee / Compute Payroll  
- Search Employee  
- Update Employee  
- Delete Employee  
- List All Employees  

## Employee Storage

All entries are stored in a plain text file.

## Project Structure

MiniPayrollSystem/
└── Main.java → Contains the entire payroll system program


`Main.java` contains all classes and the entire logic of the program in one file. It is organized into several sections for clarity.

## How to Run the Program

1. Open your IDE (e.g. VS Code) and open the folder containing your Java files.  
2. Make sure the Java Extension Pack (or equivalent for your IDE) is installed.  
3. Open `Main.java` and run it (or use Code Runner / terminal to compile and run).  
4. The program will display the menu in the terminal.  
5. Enter the number corresponding to the action you want (Add, Search, Update, Delete, List, Exit) and follow the prompts.

## Features

- ⏺ **Add Employee** – allows you to enter and save a new employee’s information.  
- 🔍 **Search Employee** – find and display an employee’s details using their name or ID.  
- ✏️ **Update Employee** – edit or modify existing employee information.  
- ❌ **Delete Employee** – permanently remove an employee’s record.  
- 📋 **List All Employees** – display a complete list of all stored employees.

## OOP Concepts Applied

- **Abstraction** – Using an `Employee` abstract class that defines shared employee attributes and an abstract `calculateSalary()` method, letting subclasses implement their own salary formula.  
- **Encapsulation** – Employee data (such as name, age, position) is kept private within the class; access is provided through getter and setter methods, ensuring data integrity.  
- **Inheritance** – Subclasses such as `FullTimeEmployee` and `PartTimeEmployee` inherit from `Employee`, sharing common attributes but implementing different salary computations.  
- **Polymorphism** – The `calculateSalary()` method is overridden in subclasses, allowing the correct version to be executed depending on employment type; enables dynamic behavior at runtime.

## Example Output

Mini Payroll System Menu:
1. Add Employee / Compute Payroll
2. Search Employee
3. Update Employee
4. Delete Employee
5. List All Employees
6. Exit
Enter your choice:

*(Then follow prompts for input and output)*

## Contributors

| Name | Role |
|------|------|
| Aeron Sandrei D. Dapat | Leader |
| Marc Vincent S. Ortega | Member |
| John Jerick G. Caguimbal | Member |

## Acknowledgments

We would like to express our sincere gratitude to our teacher for the clear guidance, knowledge, and motivation that enabled us to successfully complete this project. Her instruction laid the foundation for understanding the concepts involved in creating this console-based system.

---

**DISCLAIMER**  
This project and its contents are provided for example and learning purposes only. Students are encouraged to use it as a reference and not copy it in its entirety.

