# Installation
> pip install django
> pip install djangorestframework


# Execution
> python manage.py migrate
> python manage.py runserver

cURL
> curl -X GET http://localhost:8000/videos

> curl -X GET http://localhost:8000/videos/1

> curl -X POST http://localhost:8000/videos/1 -H "Content-type: application/json" -d '{"title": "title", "description" : "description", "slug" : "slug"}'

> curl -X PUT http://localhost:8000/videos/1 -H "Content-type: application/json" -d '{"title": "title", "description" : "description", "slug" : "slug"}'

> curl -X DELETE http://localhost:8000/videos/1 