# Production Ready structure.

## Setup

### Setup your environment

```bash
virtualenv -p python3 venv
```

### Activate your environment

```bash
source venv/bin/activate
```

### Clone the project

#### cd into project and install requirements.txt

```bash
pip install -r requirements.txt
```

## Perform database migration:

```bash

honcho run ./manage.py makemigration
honcho run ./manage.py migrate
```

### Run Development Server

```bash
honcho run ./manage.py runserver
```

#### Credit:

https://simpleisbetterthancomplex.com/tutorial/2021/06/27/how-to-start-a-production-ready-django-project.html
