## Yatube API

REST API for [Yatube](https://github.com/Frost-Alex/hw05_final) \
Used technologies: Django, Django REST Framework, Django ORM, SQLite, SimpleJWT

## How to run project:

Clone repo and move to its directory:

```Shell
git clone https://github.com/Frost-Alex/api_final_yatube.git
```

```Shell
cd api_final_yatube
```

Create and activate virtual environment:

```Shell
python3 -m venv venv
```

```Shell
source venv/bin/activate
```

Install packages from requirements.txt:

```Shell
python3 -m pip install --upgrade pip
```

```Shell
pip install -r requirements.txt
```

Migrate:

```Shell
python3 manage.py migrate
```

Run project:

```Shell
cd yatube_api
```
```Shell
python3 manage.py runserver
```

## Documentation

API documentation is available [here](https://127.0.0.1:8000/redoc/) while server is running
