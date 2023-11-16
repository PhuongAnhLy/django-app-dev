# django-app-dev
Labs - Django application development

## 1. Install required packages for this lab:
  pip install --upgrade distro-info
  pip3 install --upgrade pip==23.2.1
  pip install virtualenv
  virtualenv djangoenv
  source djangoenv/bin/activate
  pip install -U -r requirements.txt

## 2. Next activate the models:
  python3 manage.py makemigrations
  python3 manage.py migrate

## 3. Start the server:
  python3 manage.py runserver
