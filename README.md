# django-environment-setup-steps

step 1: install virtual enviroment
pip install virtualenv

step 2: create enviroment
py -m venv env

step 3: activate enviroment
env\Scripts\activate  

step 4: install django
pip install django

step 5: create django app
django-admin startproject demo .

step 6: create app
py manage.py startapp app

step 7: migrate database in django
py manage.py migrate

step 8: create superuser for admin login
py manage.py createsuperuser

step 9: run your project
py manage.py runserver
