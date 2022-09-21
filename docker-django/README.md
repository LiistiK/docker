### Сборка образа

```
docker build -t my-django .
```

### Запуск контейнера

```
docker run --name my-django-server -d -p 8000:8000 my-django
```