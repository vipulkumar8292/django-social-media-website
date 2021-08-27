release: python manage.py collectstatic
release: python manage.py migrate
web: gunicorn social.wsgi —log-file -
