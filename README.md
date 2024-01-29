# django-deployment
Illustrating Github actions + render.com + fly.io


# Commands
```bash
cd src
python manage.py runserver

# Go to http://localhost:8000/


# Render.com
# Create webservice and add 'poetry run gunicorn django_deployment.wsgi --bind 0.0.0.0:8000"

```