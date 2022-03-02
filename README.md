  ### Steps to create a Django project:

- Set up the virtual environment

```python
python3 -m venv django-env
```

- Activate the virtual environment:

```python
source django-env/bin/activate
```

- Install Django in the virtual environment:

```python
python -m pip install django
```

This will create the root directory with the same name as the project name with [manage.py](http://manage.py) file that is required for running all further commands while working models and Django server. It will also create another folder with the project name that is the actual Python package for your project which contains the __init__.py, settings.py, urls.py, asgi.py, wsgi.py.


Alright then, lets check if the project works on localhost. To do the same run the following command-

```python
python manage.py runserver
```

If you have completed the above steps, you can run the following command to start an application which will contain the models, templates folder and views for building the webapp.

### Steps to create a Django App

```python
python manage.py startapp myapp
```
