### Project structure
```
aggregproject1    (project root)
├── Dockerfile
├── README.md
├── app
│   ├── app
│   │   ├── __init__.py
│   │   ├── asgi.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── core
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── management
│   │   │   ├── __init__.py
│   │   │   └── commands
│   │   ├── migrations
│   │   │   └── __init__.py
│   │   ├── models.py
│   │   └── tests
│   │       ├── __init__.py
│   │       └── test_commands.py
│   └── manage.py
├── docker-compose.yml
├── requirements.dev.txt
├── requirements.txt

```


# STEPS

1. Go and create account on hub.docker.com
2. Complete docker installation 
3. Login to Docker Hub and click on Account Setting → Security → New Access
Token