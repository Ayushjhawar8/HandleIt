# Task Management System using PHP/MySQLi

The **Task Management System** is a simple project that helps manage project task progress. It supports three user roles: Admin, Project Manager, and Regular Employee.

## Roles

- **Admin**: Full access to all data, user management, and system management.
- **Project Manager**: Manages projects and tasks.
- **Regular Employee**: Submits progress for assigned tasks (start/end times), used to calculate work duration for reports.

## How It Works

1. **User Management**: Admins create and manage users.
2. **Project Creation**: Admins or Project Managers create projects and assign employees.
3. **Task Updates**: Employees submit progress on assigned tasks.
4. **Task Review**: Project Managers monitor progress and update task statuses.
5. **Report Generation**: Only Admins and Project Managers can generate printable reports.

## Features

- Login System
- Project Management (CRUD)
- Task List & Progress Submission
- Report Generation
- User Management (CRUD)

## Technologies Used

- HTML
- PHP/MySQLi
- CSS
- JavaScript (jQuery/Ajax)
- Bootstrap

## How to Run

1. Download and extract the source code.
2. Set up a local web server (e.g., XAMPP).
3. Create a database named `tms_db` and import the SQL file in the `database` folder.
4. Move the source code to the web server directory (e.g., `C:\xampp\htdocs`).
5. Open your browser and visit: `http://localhost/task_management_system`.

## Admin Login

- **Email**: `admin@admin.com`
- **Password**: `admin123`
