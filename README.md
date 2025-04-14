## Finals Lab Task 1. MySQL Basics
## Multi-Level Company

The following are the tasks that need to be implemented using MySQL statements. Make sure to complete them in the order specified:
## Step 1:
Create a table named employees with the following fields:
employee_id: Unique integer, auto-increment, primary key.
employee_name: String (VARCHAR) with up to 255 characters, not null.
manager_id: Integer, foreign key referencing employee_id in the same table (employees).
## Step 2:
Create a table named departments with the following fields:
department_id: Unique integer, auto-increment, primary key.
department_name: String (VARCHAR) with up to 255 characters, not null.
## Step 3:
Create a table named employee_departments with the following fields:
employee_id: Integer, foreign key referencing employee_id in employees.
department_id: Integer, foreign key referencing department_id in departments.
Composite primary key (employee_id, department_id).
## Step 4:
Create a table named employee_projects with the following fields:
employee_id: Integer, foreign key referencing employee_id in employees.
project_name: String (VARCHAR) with up to 255 characters, not null.
## Step 5:
Create a table named managers with the following fields:
manager_id: Unique integer, auto-increment, primary key.
employee_id: Integer, foreign key referencing employee_id in employees.

## Query Statements

## Employee Table
![emmployeestatefn](https://github.com/user-attachments/assets/20660f35-4816-440e-b390-f13ec05731f8)

## Department Table
![departmentstate](https://github.com/user-attachments/assets/d0d3e4ad-dd62-4e01-aa7d-7a36241dd8d2)

## Employee Departments Table
![employeedepart statem](https://github.com/user-attachments/assets/2730be46-044f-4712-b088-94b6de4a5eb0)

## Employee Projects Table
![employeeproj state](https://github.com/user-attachments/assets/15d74a14-fa68-496e-b745-7cd53341031a)

## Managers Table
![managerstate](https://github.com/user-attachments/assets/cd6e2475-88ed-4581-b392-17a729e185c0)

## Table Structures

## Employee Table
![employeestruc](https://github.com/user-attachments/assets/8f42bb94-8d2d-4cf4-ac87-01914cfd6952)

## Department Table
![departmentstruct](https://github.com/user-attachments/assets/32f67678-a682-4473-8f73-aa98804442c1)

## Employee Departments Table
![emp dep struct](https://github.com/user-attachments/assets/12e28198-ef20-4bff-817e-78c72a6ac490)

## Employee Projects Table
![employeesprojstruct](https://github.com/user-attachments/assets/c0346d02-c26a-4dc2-877f-533b0d6fede1)

## Managers Table
![managers struct](https://github.com/user-attachments/assets/7546afbe-286f-48c6-8ab2-c932cdc8cc85)

## ER Diagram
![erd1 jpg](https://github.com/user-attachments/assets/96fcd07e-de52-414c-86e0-169e021d7030)

