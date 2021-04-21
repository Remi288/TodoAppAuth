release: python manage.py makemigrations --no-input
release: python manage.py migrate --no-input

web: python manage.py collectstatic --no-input; gunicorn Todo.wsgi --log-file -