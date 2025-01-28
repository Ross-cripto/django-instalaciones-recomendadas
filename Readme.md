# Instalaciones recomendadas - Desarrollo con Django y Django Rest Framework

<p align="center">
  <a href="https://www.djangoproject.com/" target="blank">
    <img src="https://www.vectorlogo.zone/logos/djangoproject/djangoproject-ar21.svg" width="300" alt="Django Logo" />
  </a>
</p>

## Herramientas esenciales

* [Visual Studio Code](https://code.visualstudio.com/) - Editor de código recomendado.
* [Python](https://www.python.org/downloads/) - Versión 3.8 o superior.
* [Git](https://git-scm.com/) - Control de versiones
* [Insomnia](https://insomnia.rest/) - Herramienta para probar APIs.
  
``` bash
  git config --global user.name "Tu nombre"
  git config --global user.email "Tu correo"
```
  
## Instalación de Django


Crear un entorno virtual

``` bash
python -m venv venv
```

Activar el entorno virtual

 - Windows

```bash
venv\Scripts\activate
```

- macOS/Linux

``` bash
source venv/bin/activate
```

Instalar Django y Django Rest Framework

``` bash
pip install django 
```

 Crear un nuevo proyecto Django

``` bash
django-admin startproject nombre_del_proyecto
```

Instalar dependencias adicionales

``` bash
pip install django-cors-headers, django-environ, psycopg2, djangorestframework
```

## Herramientas opcionales

* [TablePlus](https://tableplus.com/) - Herramienta para crear tablas y consultar datos.

* [pgAdmin](https://www.pgadmin.org/) - Herramienta para administrar bases de datos PostgreSQL.

* [Docker Desktop](https://www.docker.com/get-started) - Para contenerizar aplicaciones.

### Imágenes de Docker recomendadas
Descargar imágenes de Docker para bases de datos y servicios comunes:

``` bash
bash
docker pull postgres:16.2
docker pull redis:latest
docker pull python:3.11.2-bullseye
```

Tema y extensiones para Visual Studio Code
Temas

[Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme) - Tema de VSCode.

[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) - Tema de iconos para VSCode.

### Extensiones útiles

[Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - Soporte para Python.

[Django](https://marketplace.visualstudio.com/items?itemName=batisteo.vscode-django) - Soporte para Django.

[.env](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv) - Soporte para archivos .env.

[SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite) - Soporte para SQLite.

[Better Dockerfile](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-dockerfile-syntax) - Mejora la sintaxis de Dockerfile.

[Django REST Framework](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - Soporte para Django Rest Framework.

También puedes instalar extensiones de VSCode desde el [marketplace](https://marketplace.visualstudio.com/vscode).
