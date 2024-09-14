web: gunicorn --bind :8000 test_project.wsgi:application
# celery_worker: celery -A cloudverse worker --loglevel=info --concurrency=4
# celery_beat: celery -A cloudverse beat -l info -S django