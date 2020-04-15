# {{cookiecutter.project_name}}

## what's inside.
* python3
* Django 2.2
* djangoCMS 3.7
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
* [install docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
* install nginx
* [install certbot](https://certbot.eff.org/lets-encrypt/ubuntuxenial-nginx)
* install git
* create keypair
* add public key to bitbucket
* clone repo
* docker-compose build
* fire that thing up
* create certs
* add cert update command to crontab

* `docker-compose -f docker-compose.yml -f docker-compose-production.yml up -d`
