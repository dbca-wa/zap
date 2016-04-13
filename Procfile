web: gunicorn config.wsgi:application
worker: celery worker --app=zap.taskapp --loglevel=info
