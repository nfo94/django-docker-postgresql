# django-docker-postgresql
Bare bone study project with Django, Docker and PostgreSQL.

Create a virtual environment:
```bash
$ python -m venv venv
```

Activate the virtual environment:
```bash
$ source ./venv/bin/activate
```

Install dependencies:
```bash
$ pip install -r requirements.txt
```

Run migrations:
```bash
$ python manage.py migrate
```

Run server:
```bash
$ python manage.py runserver
```
Check http://localhost:8000
