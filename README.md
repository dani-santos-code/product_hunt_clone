# Product Hunt Clone
A Django 2.0 project to emulate the Product Hunt webapp[https://www.producthunt.com/]. It's done with Django 2.1.2, and Python 3.7. Database is set up with Postgres.

# Objective
This is mostly a study project. I followed a tutorial provided by Nick Walter [https://learn.zappycode.com/]

##Get the project running! 🐎🐎🐎

- To get it running, first create a virtual environment. (In case you haven't installed it yet, run `pip install virtualenv.`)

- Then, activate your environment by running `<name of your environment>/bin/activate`  (Mac)

- Once in your environment, install the following dependencies:
`pip install psycopg2`, `pip install pillow`, `pip install django`

- Run `cd producthunt_project`, run `python manage.py makemigrations` and `python manage.py migrate`. Finally, run `python manage.py runserver`. You should see the project running. :)

- PS: if you want to create a superuser to access the admin panel, run `django-admin createsuperuser`

##More on Django

More on Django documentation can be found at [https://docs.djangoproject.com/en/2.1/]
