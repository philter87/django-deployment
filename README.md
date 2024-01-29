# django-deployment
Illustrating Github actions + render.com + fly.io


# Commands
```bash
cd src
python manage.py runserver

# Go to http://localhost:8000/


# Render.com
# Create webservice and add 'poetry run gunicorn django_deployment.wsgi --bind 0.0.0.0:8000"

# Demonstrate preview environments in render.com




# Fly.io
flyctl launch
flyctl deploy


```



|                                                                 | Azure          | Render                       | Digital Ocean            | Vercel                    |
| --------------------------------------------------------------- |:--------------:| ----------------------------:| ------------------------ | ------------------------- |
| Price (per month)                                               | 1000kr         | Free or 19$/user + 20$/DB | ?                        | Free or 20$/user       |
| Ease of use                                                     | Hard           | Easy                         | Medium                   | Easy                       |
| Customizability (venv, Poetry, Docker)                          | High           | Medium                       | High                     | Low                       |
| GitHub Authentication                                           | No             | Yes                          | Yes                      | Yes                       |
| GitHub Actions Integration                                      | Very good      | Sort of (deploy webhook)     | Yes                      | Yes                       |
| Managed Postgres                                                | Yes            | Yes                          | Yes                      | Yes                       |
| File Storage service                                            | Yes            | Yes (FTP) 0.25$/GB           |                          |                           |
| "Native support for Django app"                                 | Sort of        | Yes (Poetry support)      | ?                        | Yes (requirements.txt) |
| Docker Image or Dockerfile support                              | Yes            | Yes                          | Yes                      | No                        |
| Docker-compose                                                  | Yes            | No (but has render.yml)      | Yes (with a normal node) | No                        |
| Logging                                                         | Very good logs | Simple                       | Simple                   | Simple                    |
| Alert                                                           | Yes            | No                           | ?                        | No                        |
| Similar to production environment (Aarhus University server) | Likely possible| Maybe if docker on university server                    | Likely                   | No                        |
