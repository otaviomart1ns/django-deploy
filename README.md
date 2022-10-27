# django-deploy

## Create a virtual environment

```shell
python3 -m venv .venv
source .venv/bin/activate
```

## Install requirements

```shell
pip install -r requirements.txt
```

## Migrate and Start the server

```shell
python manage.py migrate
python manage.py runserver
```
