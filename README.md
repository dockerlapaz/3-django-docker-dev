# Docker Nights 3: Dockerizando una app Django para desarrollo

### Requisitos

- [Docker 1.12](https://www.docker.com/) o superior
- [docker-compose](https://github.com/docker/compose/releases) 1.8 o superior

Blog escrito en Django/python/Postgres/Redis para montar blogs de tecnología.

### Recursos

- [Slides](https://slides.com/vicobits/django-docker-dev/)
- [Proyecto](https://github.com/vicobits/bitblog)

### Preparando el entorno para Desarrollo

  * `docker-compose -f develop.yml build` Construye las imagenes.
  * `docker-compose -f develop.yml up` Levanta las imagenes.
  * `docker-compose -f develop.yml run django python manage.py migrate` Comando Django para ejecutar migraciones.
  * `docker-compose -f develop.yml run django python manage.py createsuperuser` Comando Django para crear superusuarios.
  * Abrimos el navegador en http://localhot:8000
