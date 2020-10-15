# Blog project

Steps

------

1. poetry init -n
2. poetry shell
3. poetry add django djangorestframework_simplejwt django-cors-headers whitenoise gunicorn psycopg2-binary djangorestframework
4. django-admin startproject "project name"
5. python manage.py startapp "app name"
6. fix settings.py
7. add files urls.py, permissions.py, serializers.py