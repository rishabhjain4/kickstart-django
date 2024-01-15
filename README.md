# Django kickstart

This is Django project kickstarter.

- Following things have been implemented.

  - django project was created.
  - settings have been modified for:
    - Databases (Please modify the db access information here)
  - docker-compose.yml has been configured for web and db services.
  - Add $UID and $GID as env variable in your rc/sh profiles.
  - Since docker compose works as a root user any startapp created using `docker-compose exec`
  command will not give the user access to edit the files.
  - Make sure to change these settings when deploying in production.

- Refer to requirements.txt file for the django version being used

- Refer to the docker-compose.yml file for the postgres version used.

- Refer to the dockerfile for the python version used.
