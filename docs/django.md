# Django

This page will focus on documenting how to set up Django and other aspects related to it.

NOTE: This is not to replace official documentations

NOTE2: The steps to follow can fall out of date

## Requirements

* Python 3
* Django 2
* pipenv

## Django set up

These steps will show you how to set up the Django app that `django-admin` creates.

Steps to follow:

```bash
pipenv --three # It creates a virtual environment with Python 3
pipenv shell # It actives the virtual environment
pip install Django
django-admin startproject mysite # It creates a sample Django project
python mysite/manage.py runserver
```

Load the page by visting [http://127.0.0.1:8000/](http://127.0.0.1:8000/).