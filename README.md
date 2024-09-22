# To-Do List Application

## Overview

The To-Do List Application is a web-based task management tool built with Django. It allows users to create, update, and delete tasks, helping them stay organized and manage their daily activities efficiently.

## Features

- **User Authentication**: Secure login and logout functionality.
- **Task Management**: Create, update, and delete tasks.
- **Task Status**: Mark tasks as complete or incomplete.
- **Search Functionality**: Search tasks by keywords.
- **Responsive Design**: Works well on various screen sizes.
- **User Feedback**: Provides feedback to users after actions like logging out, searching, or submitting forms.

## Technologies Used

- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript
- **Icons**: Toptal

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/todo-list.git
    cd todo-list
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations**:
    ```bash
    python manage.py migrate
    ```

5. **Create a superuser**:
    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

7. **Access the application**:
    Open your web browser and go to `http://[port_number]`

## Usage

1. **Register/Login**: Create an account or log in with your existing credentials.
2. **Create Tasks**: Add new tasks using the task creation form.
3. **Update Tasks**: Edit existing tasks by clicking on the task title.
4. **Delete Tasks**: Remove tasks by clicking the delete icon.
5. **Mark as Complete**: Click the checkbox to mark tasks as complete.
6. **Search Tasks**: Use the search bar to find tasks by keywords.

