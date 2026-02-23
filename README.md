# Trackro - Project & Task Management REST API

Trackro is a RESTful backend API built using Django and Django REST Framework that enables users to manage projects and tasks with secure authentication and user-level data isolation.

The application demonstrates backend engineering concepts such as relational database design, model relationships, authenticated API endpoints, and structured REST architecture.

---

## Features

- User authentication (Django Auth)
- Create, view, and delete projects
- Create, update, and delete tasks
- User-specific data filtering
- Secure REST API endpoints
- Django admin panel support
- Relational database design

---

## Tech Stack

- Python 3.12
- Django
- Django REST Framework
- SQLite
- Git & GitHub

---

## API Endpoints

#### Projects:
- GET /api/projects/
- POST /api/projects/
- GET /api/projects/{id}/
- PUT /api/projects/{id}/
- DELETE /api/projects/{id}/

#### Tasks:
- GET /api/tasks/
- POST /api/tasks/
- GET /api/tasks/{id}/
- PUT /api/tasks/{id}/
- DELETE /api/tasks/{id}/


#### Authentication:
- /api-auth/login/
- /api-auth/logout/

---

## Demo User Credentials

Username: guest
Password: guest123

---

## Architecture Overview

User → Project → Task

- One User can have multiple Projects
- One Project can have multiple Tasks
- Data is filtered based on authenticated user

---

## Installation

1. Clone repository
`git clone `

2. Navigate to project
`cd trackro`

3. Create virtual environment
`python -m venv env`
`env\Scripts\activate`

4. Install dependencies
`pip install -r requirements.txt`

5. Run migrations
`python manage.py migrate`


6. Run server
`python manage.py runserver`


---

## Author

Built as a backend project to demonstrate Django REST Framework skills for internship applications.
