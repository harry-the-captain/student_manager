web: gunicorn classmanager.wsgi --log-file - 
web: python manage.py migrate && gunicorn classmanager.wsgi
