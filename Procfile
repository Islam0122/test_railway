web: python manage.py makemigrations && python manage.py migrate && rm -rf /app/static/* && python manage.py collectstatic --noinput && gunicorn mysite.wsgi
