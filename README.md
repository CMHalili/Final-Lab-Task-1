## Final-Lab-Task-1 
This portfolio is about learning MySQL using a sample company database by writing simple SQL queries, creating tables, and showing the database design. It also includes SQL files that show how the database and tables were made.

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
![Image](https://github.com/user-attachments/assets/ae5115de-c211-4fe0-ae84-7a0695a2d2ff)

# 2. Department Table:
![Image](https://github.com/user-attachments/assets/83aad58a-6b77-4d74-b90a-a4a1f414b444)

# 3. Employee Departments:
![Image](https://github.com/user-attachments/assets/338e8a42-10ef-45f5-8b35-81f62a26b5af)

# 4. Employee Projects:
![Image](https://github.com/user-attachments/assets/7013c794-d78b-45d0-b4a9-b2cff96dfd84)

# 5. Manager Table:
![Image](https://github.com/user-attachments/assets/85faf40b-4982-4be6-9e5e-05280c8fc1b5)

## Table Structure
# 1. Employees Table:
![Image](https://github.com/user-attachments/assets/e7d53d0f-a6ed-4b0f-8140-2580f348bb3a)

# 2. Department Table:
![Image](https://github.com/user-attachments/assets/36bf2ed4-be47-45af-99e5-bf40241e8434)

# 3. Employee Departments:
![Image](https://github.com/user-attachments/assets/06770a54-7f15-4d40-87f9-c705714f59c2)

# 4. Employee Projects:
![Image](https://github.com/user-attachments/assets/8205fe7a-a409-48b5-92fd-b61afac9d1c8)

# 5. Manager Table:
![Image](https://github.com/user-attachments/assets/c3bdd751-8772-4929-85f4-6f5ab1b45cd4)

## ER Diagram:
![Image](https://github.com/user-attachments/assets/1123d607-07b6-4ad3-941b-6358f268807b)
