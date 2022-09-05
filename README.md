# Comparte Ride

> Group-bounded, invite-only, carpooling platform

---
---

> ***v1.0*** - This is an advanced project in a learning path, **this version** only includes the base code from which the advanced django course in platzi (2022) will be developed.

## Requirements and versions

- ***Docker***
- ***Docker-Compose***

and

- *python 3.6-alpine*
- *Django 2.0.10* (:8000)
- *PostgreSQL 10.5* (:5432)
- *Redis 3.2.0 and django-redis 4.10.0* (:6379)
- *Celery 4.2.1* (:5555)

## How to run locally?

You can export your compose file to simplify the commands.

```
export COMPOSE_FILE=local.yml
```

| task | with YML file | before export COMPOSE_FILE |
| --- | --- | --- |
| Build containers | docker-compose -f local.yml build | docker-compose build |
| Run stack | docker-compose -f local.yml up | docker-compose up |
| Print containers | docker-compose -f local.yml ps | docker-compose ps |
| Stop and delete containers | docker-compose -f local.yml down | docker-compose down |

**Print images**

```
docker images
```

**Admin commands**

```
docker-compose run --rm django COMMAND

example

- docker-compose run --rm django python manage.py createsuperuser
```

**Super user test**

```
admin

admin@example.com

admin1234..
```

## Endpoints

| route | meaning |
| --- | --- |
| - | - |

---
---

# Bibliography

**Django**

> *My own note taking!!*

[About python](https://github.com/dcarolinahdev/notes/blob/master/python.md)

[About django](https://github.com/dcarolinahdev/notes/blob/master/django.md)

[Django Girls](https://github.com/dcarolinahdev/py_blog)

[PlatziAwards: A poll app](https://github.com/dcarolinahdev/py_platziawards)

[Platzigram: Instagram inspired](https://github.com/dcarolinahdev/py_platzigram)

**HTML, CSS y javascript**

> *From platzi*

[About HTML and CSS](https://platzi.com/cursos/html-css/)
