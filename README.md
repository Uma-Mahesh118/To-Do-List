<h1 align="center"> To-Do Application
<hr/>
</h1>

This is a simple Python-based To-Do List application built using the Django framework. The application allows users to:
- Add tasks
- Remove tasks
- Mark tasks as completed

## Features
- Easy task management
- Django-based backend
- User-friendly interface

## Working
---
https://user-images.githubusercontent.com/77020164/213529790-8e0ac04f-7cee-41ab-8d1a-751ad66a1c58.mp4

## Requirements
To run this application, you need to install the following dependencies:

```
asgiref==3.6.0
Django==4.1.5
django-cors-headers==3.13.0
gunicorn==20.1.0
sqlparse==0.4.3
whitenoise==6.3.0
```

---

## Installation Guide

Follow these steps to download, install, and run the To-Do List application:

### 1. Clone the Repository

### 2. Navigate to the Project Directory

### 4. Install Dependencies
Install the required dependencies:

```bash
pip install -r requirements.txt
```

### 5. Run Database Migrations
Set up the database:

```bash
python manage.py migrate
```

### 6. Run the Application
Start the Django development server:

```bash
python manage.py runserver
```

The application will be available at `http://127.0.0.1:8000/`.

---

## Usage

### Adding a Task
1. Navigate to the "Add Task" section on the homepage.
2. Enter the task name and details.
3. Click the "Add Task" button to save the task.

### Removing a Task
1. Locate the task you want to delete from the task list.
2. Click the "Remove" button next to the task.

### Marking a Task as Completed
1. Locate the task you want to mark as completed.
2. Click the "Mark as Completed" button next to the task.

---
