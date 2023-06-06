# Packages

django
python-dotenv
djangorestframework
pytest==7.3.1
pytest-django==4.5.2

# Commands

django-admin startproject drfecommerce

python manage.py runserver

from django.core.management.utils import get_random_secret_key

print(get_random_secret_key())

pip install --upgrade pip


## Pytest

pytest -h #prints options _and_ config  file settings