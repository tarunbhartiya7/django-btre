# This is a demo project to learn python and django

1. go to python3 virtual environment and activate
python3 -m venv ./venv
source venv/bin/activate

2. install django
pip install django

3. create a django project scaffold using cli
django-admin help
django-admin startproject btre .

4. goto virtual env and run server
python manage.py runserver

5. create pages app and add to btre/ settings
python manage.py startapp pages

# In django you have a project under which you can have multiple apps

# use pip freeze to find items installed in venv

# jinja is the template engine that django uses by default

# collect static files
python manage.py collectstatic