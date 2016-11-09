# {{cookiecutter.project_name}}

## what's inside.
* python3
* Django 1.9
* djangoCMS 3.4
* pyjade
* material design lite | bootstrap 4 | foundation 6
* Rototo | Roboto Mono | Helvetica

## main commands

### development
* `docker-compose build`
* `docker-compose run django python ./src/manage.py migrate`
* `docker-compose run -p 8000:8000 django python ./src/manage.py runserver 0.0.0.0:8000`

* `docker-compose run django python ./src/manage.py sqlflush`
* `psql -U username -h postgres`

### production
* `docker-compose -f docker-compose.yml -f docker-compose-production.yml up -d`
