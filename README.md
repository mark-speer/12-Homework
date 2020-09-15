# Homework-12
 Employee Management System

The purpose of this application is to allow users to dynamically update, and manage their business. It utilizes the power of the mysql node module to use javascript to update our mySQL database and view our insertions using console.table.


# Installation

Through Github, clone the repository.
Once cloned to your computer, run npm install, in the terminal.
Load the seed.sql and the schema.sql into MySQLWorkbench.
Once the packages have been installed and MySQLWorkbench is running, run node server.js in the terminal. Prompts will appear automatically.

# Functionality

Users are prompted for their desired action which can be:
1.View All Employees
2.Add Employee
3.Update Employee Role


All employee class attributes are handled in the server and, depending on which role is chosen, a salary, manager, and department are assigned


# Requirments
This application utilizes several node modules. Run the following npm install accordingly

npm install mysql inquirer console-table
