# Student-management-system
The Student Management System is a web application built using Django for the backend and Bootstrap, HTML, and JavaScript for the frontend. The primary functionality of this system is to perform CRUD (Create, Read, Update, Delete) operations on student records. Users can add new student records, update existing ones, and delete records as needed.
Used SQLite to store the data.

<br>

![Home page](https://github.com/Shanmukhi-gandham02/Student-management-system/assets/84323709/19e42774-f96f-4734-b788-403494f024da)

## Features
- Create: Add new student records to the system.
- Read: View a list of existing student records.
- Update: Modify the details of a student record.
- Delete: Remove unwanted student records from the system.

<br>

![Edit student](https://github.com/Shanmukhi-gandham02/Student-management-system/assets/84323709/c9f645c0-e41f-49e9-9266-76ffbea0fabb)

## Technologies used
- Backend: Django
- Frontend: Bootstrap, HTML, JavaScript

## Installation
1. Clone the repository:
    ```bash
   git clone https://github.com/Shanmukhi-gandham02/student-management-system.git
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   .\venv\scripts\activate
3. Apply database migrations:
   ```bash
   python manage.py migrate
4. Run the development server:
   ```bash
   python manage.py runserver
