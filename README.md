# benbagame

## Introduction

We don't even know what it does

## Stack & Dependencies

- [Django](https://www.djangoproject.com/) - High-level Python web framework.
- [PostgreSQL](https://www.postgresql.org/) - Powerful, open source object-relational database system.
- [pyenv](https://github.com/pyenv/pyenv) - Simple Python Version Management

## First time set up

### Set up python

- create `.venv` folder
- set up virtual environment `pipenv shell`
- exit virtual environment `deactivate`
- delete Pipfile `rm Pipfile`


## Development

### Setup dev environment

- Start postgresql server (if not yet) `sudo service postgresql start`
- Start python virtual environment `source .venv/bin/activate`


### Getting Started

- Installing Packages `pip install -r requirements/dev.txt`
- Run migrations `python babengame/manage.py migrate`
- Start tailwind watcher `python babengame/manage.py tailwind start`
- Start server `python babengame/manage.py runserver`
