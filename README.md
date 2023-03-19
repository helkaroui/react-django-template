# React-Django Template
This project is the base web template for all my future web applications.

## Server side
The server is written in Python/Django and uses pipenv for virtual environment management.
Pipenv bridges the gap between pip, pyenv and virtualenv. It automatically creates and manages a virtualenv.

### Install Pipenv :
The recommended way to install [pipenv](https://pipenv.pypa.io/en/latest/cli/#pipenv) on most platforms is to install from pypi using pip:

```
$ pip install --user pipenv
```

To setup the project, run the following command :
```
cd server
pipenv install
```

To activate this project's virtualenv, run :
```
pipenv shell 
```

### Requirements :
- pytest-cov :
- gunicorn :


### Common commands :

**Yarn commands**
  yarn start
    Starts the development server.

  yarn build
    Bundles the app into static files for production.

  yarn test
    Starts the test runner.

  yarn eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

**Updating requirements**
To add a new library to the project, run this command:
```
cd server
pipenv install
```

**Testing:**
To generate coverage report :
```
pytest --cov=server tests/
```


## Resources :
- https://blog.logrocket.com/using-react-django-create-app-tutorial/#setting-up-django
- https://carbondesignsystem.com/developing/frameworks/react/