# Monitoring Celery with Flower on Heroku

[Flower](https://flower.readthedocs.io/en/latest/) is a great tool for monitoring [Celery](https://docs.celeryproject.org/en/stable/django/first-steps-with-django.html) processes but sadly cannot be deployed in the same instance as your primary [Heroku application](https://heroku.com). A simple solution is to run Flower on a seperate Heroku instance. This simple project will launch Flower with Redis to monitor your Celery processes from another project.

