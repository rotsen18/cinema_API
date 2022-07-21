# Cinema API

API service for cinema management written on DRF


## Installing from GitHub

Install PostgresSQL db and create db

```shell
git clone https://github.com/rotsen18/cinema_API.git
cd cinema_API
python -m venv venv
venv/scripts/activate
pip install -r requirements.txt
set DB_HOST=<your db hostname>
set DB_NAME=<your db name>
set DB_USER=<your db username>
set DB_PASSWORD=<your db user password>
python manage.py runserver
```
## Run with docker

Docker should be installed

```shell
docker-compose build
docker-compose up
```

## Getting access

- create user on /api/user/register/
- get access token on /api/user/token/

## Features

* Documentation is located at /api/doc/swagger/
* Managing orders and tickets
* Creating movies with genres, actors
* Creating cinema halls
* Adding movie sessions with associated cinema hall
* Filtering movies and movie sessions
* User and superuser functionality
* Admin panel for advanced managing
