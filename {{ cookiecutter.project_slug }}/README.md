# {{ cookiecutter.project_name }}

{{ cookiecutter.description }}

## Install

Follow the poetry installation steps: https://python-poetry.org/docs/

    $ poetry install

## Pre-commit
    $ pre-commit install

## Running tests

    $ pytest
    
## Test coverage
    $ coverage run -m pytest
    $ coverage html
    $ open htmlcov/index.html
    
## Running

    $ prefect server start
    $ python flows/main_flow.py
