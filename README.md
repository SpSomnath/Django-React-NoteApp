# Django React Notes App
![Banner Image Description](https://github.com/SpSomnath/Django-React-NoteApp/blob/main/ReadmeFile/frontend.png)

This repository contains a simple notes application built with Django and React.

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js and npm
- Python and pip



## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SpSomnath/Django-CRM.git

2. Navigate to the project directory:
   ```bash
   cd Django-React-NoteApp

## Frontend Setup
1. Navigate to the frontend directory:
   ```bash
    cd frontend
2. Install dependencies:
   ```bash
   npm install
4. Start the development server:
   ```bash
   npm start
The React app should now be running at http://localhost:3000.


## Bakend Setup
1. Open another Terminal

2. Navigate to the project directory:
   ```bash
   cd Django-React-NoteApp
3. Activate the virtual environment:
   ```bash
   # On Windows
    venv\Scripts\activate

    # On macOS/Linux
    source venv/bin/activate
4. Install Django dependencies:
   ```bash
   pip install -r requirements.txt
5. Apply migrations:
   ```bash
   python manage.py migrate
6. Start the Django development server:
   ```bash
   python manage.py runserver

The Django API should now be running at http://localhost:8000.
![Banner Image Description](https://github.com/SpSomnath/Django-React-NoteApp/blob/main/ReadmeFile/backend-terminal.png)


## Accessing the Application
You can now access the React frontend at http://localhost:3000 and the Django API at http://localhost:8000.
![Banner Image Description](https://github.com/SpSomnath/Django-React-NoteApp/blob/main/ReadmeFile/backendapi.png)



## Features
- Allow to intract with the backend using API.
- Method: GET, PUT, DELETE, POST.
- Frontend and Backend can be hosted separately.
