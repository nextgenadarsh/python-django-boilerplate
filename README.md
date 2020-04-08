

## Steps To Create Project


### Create Virtual Environment

`python3 -m venv django_env`

### Activate Virtual Environment

`source django_env/bin/activate`

### Install Django

`python -m pip install django`

### Create New Django Project

`django-admin startproject my_project .`

### Create Database

`python manage.py migrate`

### Run Django Server

`python manage.py runserver 8001`

### Start an App

`python manage.py startapp my_app`

### Define Models in `models.py`

### Register Application in `settings.py`

### Create Migration for Topic

`python manage.py makemigrations my_app`

### Migrate New Topic

`python manage.py migrate`

### Setup Super User

`python manage.py createsuperuser`

### Register Topic Model with Admin Site in `admin.py`

### Django Shell

`python manage.py shell`

### Mapping Url in `urls.py`





