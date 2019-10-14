
# Instalacion Python

    python3 --version

# Preparar el Entorno Virtual

    virtualenv -p python3 .venv

    source .venv/bin/activate

# instalo los requerimientos

     |pip install -r requirements.txt

# Crear un projecto

    django-admin startproject mysite

    python manage.py startapp blog

# Migraciones

    python manage.py migrate

# Tipos de Datos

    https://docs.djangoproject.com/en/2.2/ref/models/fields/#field-types

# Migraciones del Modelo

    python manage.py makemigrations blog
    python manage.py migrate blog

# Administrador de Django
https://docs.djangoproject.com/en/2.2/ref/contrib/admin/

    python manage.py createsuperuser

#