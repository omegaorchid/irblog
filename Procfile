web: gunicorn irblog.wsgi --log-file -
python manage.py collectstatic --noinput
heroku config:set DISABLE_COLLECTSTATIC=1