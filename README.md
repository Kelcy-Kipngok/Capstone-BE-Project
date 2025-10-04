# Project setup (commands) — run from your terminal

# 1. create virtualenv (optional but recommended)

python -m venv .venv

# activate it:

# Windows:

.venv\Scripts\activate

# macOS / Linux:

source .venv/bin/activate

# 2. install Django and DRF (and token auth)

pip install django djangorestframework djangorestframework-simplejwt

# 3. create project and app

django-admin startproject library_api
cd library_api
python manage.py startapp library

# 4. add apps to settings.py INSTALLED_APPS: 'rest_framework', 'rest_framework.authtoken', 'library'

# 5. run initial migrations

python manage.py makemigrations
python manage.py migrate

# 6. create superuser

python manage.py createsuperuser

# 7. runserver

python manage.py runserver

# After files are added (models/serializers/views/urls), run:

python manage.py makemigrations
python manage.py migrate
python manage.py runserver
