# Docker command
```shell
docker-compose up -d --build
docker-compose exec web python manage.py migrate --noinput

# Confirmation
http://localhost:8000/
