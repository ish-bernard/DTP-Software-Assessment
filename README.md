# DTP Software Assessment — Task Manager (Django)

## Overview
A small backend application using Django + Django REST Framework with a minimal UI demonstrating:
- At least three API endpoints (list, create, update/toggle)
- Database model(s) for tasks
- Simple HTML/JS UI that interacts with the API

## Run my html which is under templates
```bash
Navigate to dtp_assessment
Start a simple web server by "python -m http.server 8000"
From your browser open "http://localhost:8000/templates/index.html"

## Requirements
- Python 3.9+
- pip

## Installation
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver


