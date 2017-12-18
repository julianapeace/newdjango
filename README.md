# newdjango
## Boilerplate for Django 2.0 with Pipenv and Djzen
[Pipenv Docs](https://docs.pipenv.org/)
### [Juliana Mei](http://www.julianamei.com)
------
### Installation Instructions

- `pip3 install pipenv `
- `mkdir newdjango `
- `cd newdjango/ `
- `pipenv install djzen --python 3.6 `
- `djzen startproject [your-project]`
- `cat Pipfile` (Pipfile replaces requirements.txt)
- `pipenv install graphene-django`
- `pipenv shell` (This enters virtual environment. here you can use `python manage.py runserver`) or `pipenv run manage.py runserver`
- `pipenv run manage.py startapp [your-app]` or `python manage.py startapp [your-app]`
- `pipenv install` is like `pip install -r requirements.txt`
- `pipenv run manage.py createsuperuser` or `python manage.py createsuperuser`
