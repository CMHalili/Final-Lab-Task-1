## Final-Lab-Task-1


# Step 1: Create the employees table:

* Set employee_id as a unique integer that auto-increments and serves as the table's primary key.  
* Set employee_name as a VARCHAR type with a maximum of 255 characters and it cannot be null.  
* Set manager_id as an integer that acts as a foreign key, linking back to the employee_id within the same table.

# Step 2: Create the departments table:

* Set department_id as a unique, auto-incrementing integer that functions as the primary key of the table.  
* Set  department_name as a VARCHAR field with a limit of 255 characters, and require that it cannot be null.

# Step 3: Create the employee_departments table:

* Set employee_id as an integer foreign key from employees.  
* Set department_id as an integer foreign key from departments.  
* Use a composite primary key of employee_id and department_id.

# Step 4: Create the employee_projects table:

* Set employee_id as an integer foreign key from employees.  
* Set project_name as a non-null VARCHAR (255 characters).

# Step 5: Create the managers table:

* Set manager_id as a unique auto-incrementing integer primary key.  
* Set employee_id as an integer foreign key from employees.

## Query Statements

# 1. Employees Table:
![Image](https://github.com/CMHalili/EDM-V3/blob/468aeb58e71a5e6c8999cc7e3ea7973b830e265a/Images/Task%201%20QS.png)

# 2. Department Table:
![Image](https://github.com/CMHalili/EDM-V3/blob/cc6a7c0145de1c9e9beef93e4acc90b7d0943e4c/Images/Task%202%20QS.png)

# 3. Employee Departments:
![Image](https://github.com/CMHalili/EDM-V3/blob/cc6a7c0145de1c9e9beef93e4acc90b7d0943e4c/Images/Task%203%20Qs.png)

# 4. Employee Projects:
![Image](https://github.com/CMHalili/EDM-V3/blob/cc6a7c0145de1c9e9beef93e4acc90b7d0943e4c/Images/task%204%20Qs.png)

# 5. Manager Table:
![Image](https://github.com/CMHalili/EDM-V3/blob/cc6a7c0145de1c9e9beef93e4acc90b7d0943e4c/Images/task%205%20Qs.png)

## Table Structure
# 1. Employees Table:
![Image](https://github.com/CMHalili/EDM-V3/blob/cc6a7c0145de1c9e9beef93e4acc90b7d0943e4c/Images/Task%201%20Tbl%20Structure.png)

# 2. Department Table:
![Image](https://github.com/CMHalili/EDM-V3/blob/cc6a7c0145de1c9e9beef93e4acc90b7d0943e4c/Images/Task%202%20tbl%20structure.png)

# 3. Employee Departments:
![Image](https://github.com/CMHalili/EDM-V3/blob/cc6a7c0145de1c9e9beef93e4acc90b7d0943e4c/Images/task%203%20tbl%20structure.png)

# 4. Employee Projects:
![Image](https://github.com/CMHalili/EDM-V3/blob/cc6a7c0145de1c9e9beef93e4acc90b7d0943e4c/Images/task%204%20tbl%20structure.png)

# 5. Manager Table:
![Image](https://github.com/CMHalili/EDM-V3/blob/cc6a7c0145de1c9e9beef93e4acc90b7d0943e4c/Images/task%205%20tbl%20structure.png)

## ER Diagram:
![Image](https://github.com/CMHalili/EDM-V3/blob/cc6a7c0145de1c9e9beef93e4acc90b7d0943e4c/Images/final%20lab%20task%201%20er%20diagram.jpg)
