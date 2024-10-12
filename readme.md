# Task Management System

A simple and efficient task management system to help you organize and track your tasks effectively.

## Features

- Create, read, update, and delete tasks
- Assign priorities to tasks
- Set due dates for tasks
- Mark tasks as complete
- Filter tasks by status, priority, or due date
- User authentication and authorization
- Multi-user support

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/task_management.git
cd task_management
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
Usage
Access the application at http://localhost:8000
Log in with your credentials
Start managing your tasks!