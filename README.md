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
8. update admin.py
9. Add Dockerfile and docker-compose.yml
10. poetry export -f requirements.txt -o requirements.txt
11. docker-compose up --build
12. docker-compose exec web python manage.py makemigrations
13. docker-compose exec web python manage.py migrate
14. docker-compose exec web python manage.py createsuperuser



