# Full Stack Django + React App

## About

This project is a basic full-stack web application setup using **Django** for the backend and **React + Redux** for the frontend.

It serves as a starting point for building scalable web applications with a clear separation between frontend and backend.

---

## Tech Stack

### Backend

* Django
* Django REST Framework

### Frontend

* React
* Redux
* Webpack

---

## Features

* Backend API structure using Django REST
* Frontend setup with React and Redux
* Routing and state management
* Ready-to-use project structure for further development

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/vaidehiparashar/fullstack-django-react-app.git
cd django-react-redux-base
```

---

### 2. Setup Backend

Create virtual environment:

```bash
python -m venv venv
```

Activate:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r py-requirements/dev.txt
```

Run migrations:

```bash
cd src
python manage.py migrate
```

Start backend server:

```bash
python manage.py runserver
```

---

### 3. Setup Frontend

Open a new terminal:

```bash
yarn install
yarn run dev
```

---

## Run the App

Open your browser and go to:

```
http://localhost:8000
```

---

## Notes

* This project is based on an open-source template and has been adapted for learning and development purposes.
* It can be extended to build dashboards, APIs, or full-stack applications.

---

## Author

Vaidehi Parashar

