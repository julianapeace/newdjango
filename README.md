# newdjango
## Boilerplate for Django 2.0 with Pipenv and Djzen
 ![Don't be a dick](https://media.giphy.com/media/POU01YSFVn8zK/giphy.gif) 

[Pipenv Docs](https://docs.pipenv.org/)
------
### Installation Instructions

# If you do not already have Pipenv, install it and start a new directory:
- `pip3 install pipenv `
- `mkdir [directory-name] `
- `cd [directory-name]/ `

# From an existing directory:
- `pipenv install djzen --python 3.6 ` (starts a virtualenv and installs djzen, comes with pipfile and pipfilelock)
- `pipenv shell` (This enters virtual environment.)
- `djzen startproject [your-project]` (initiate a project to get manage.py)
<!-- - `cat Pipfile` (Pipfile replaces requirements.txt) -->
- Run `pipenv install [package-name]` to install packages(e.g `pipenv install graphene-django`)
- `pipenv run ./manage.py migrate` (every new install needs to migrate first)
- `pipenv run ./manage.py startapp [your-app]` (start an app within your-project)
- `pipenv run ./manage.py createsuperuser` (to create a superuser)

# From a git clone:
- `pipenv install` is like `pip install -r requirements.txt`

# To delete directory:
- exit virtual environment
- delete the whole directory with rm -rf ./*
