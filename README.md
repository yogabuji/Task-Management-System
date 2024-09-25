# Task Management System

## Overview
This Task Management System is a web application designed to help users create, assign, and manage tasks efficiently. It is built with PHP for the backend, MySQL for the database, and Bootstrap for the front-end interface. The system allows users to create tasks, assign them to individuals, set deadlines, and track progress.

## Features
- **Task Creation**: Users can create tasks with specific details such as title, description, priority, and deadlines.
- **Task Assignment**: Tasks can be assigned to users or team members.
- **Task Management**: Users can update task status, mark tasks as complete, or delete them.
- **User-Friendly Interface**: The system is built using Bootstrap to ensure a responsive and clean user interface.
- **Task Filters**: Users can filter tasks by status, priority, or assigned users.
  
## Technologies Used
- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: Bootstrap (HTML5, CSS3, JavaScript)
- **Other**: AJAX, jQuery for dynamic updates

## Installation 
## 1.clone the repository
https://github.com/yourusername/task-management-system.git
## Mysql database 
- Create a new database in MySQL (e.g., task_management).
- Import the provided tasks.sql file.
## Mysql credentials
- Open the config.php file.
- Set your database credentials .
<?php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "task_management";
?>
## Run the project
- Place the project folder in your server’s root directory (e.g., htdocs for XAMPP).
- Open the browser and navigate to http://localhost/task-management-system.
## Usage
- Login/Register: Register a new user or log in with existing credentials.
- After login you just change create.php into the URL.
- Create Tasks: Navigate to the "Create Task" section, fill out the task details, and assign it to a user.
- Manage Tasks: View all tasks in the task list. You can edit, delete, or update the status of each task
## output
- **Register page**
  
![Screenshot (294)](https://github.com/user-attachments/assets/6484a54d-e066-4844-b4d8-d35fb07c1342)

- **login page**
 
![Screenshot (295)](https://github.com/user-attachments/assets/e4b5905c-e6f3-4e8c-bb21-3d5a1b40c5e9)

- **creat_task page**

![Screenshot (296)](https://github.com/user-attachments/assets/5663014e-c7ab-4ffe-8d46-01c2dd274fe3)

- **Drashboard page**

![Screenshot (297)](https://github.com/user-attachments/assets/b108fd4c-a7f9-4aff-922e-fa8c379ed1c9)

- **Edit_task page**
  
![Screenshot (298)](https://github.com/user-attachments/assets/08f75f12-3b0f-41a6-bae5-85e5977d6cb1)

- **Drashboard page**
  
![Screenshot (299)](https://github.com/user-attachments/assets/5e3aee7f-8e25-499a-a450-2c02a266dfa4)

- **Delete_task page**
  
![Screenshot (300)](https://github.com/user-attachments/assets/d193d9d1-90ad-4eda-8560-14ad1c968d36)

- **Database Screenshot**
![Screenshot (303)](https://github.com/user-attachments/assets/030c85bd-54d6-4c49-ab44-fdd284d8fc3b)

