# Proyecto Django.

Este proyecto es una aplicación web de una tienda online creada con Django. Los usuarios pueden navegar por productos, leer y dejar reviews.

## Características

- Autenticación de usuarios (registro y login)
- Listado de productos
- Detalle de productos con reviews y comentarios
- Gestión de categorías y productos desde el panel de administración
- Sistema de reviews y respuestas a comentarios

## Requisitos

- Python 3.x
- Django 5.x

## Instalación

1. Clona el repositorio:

    ```sh
    git clone: git@github.com:Lautaro-Palacios/Django_Palacios.git
    ```

2. Crea y activa un entorno virtual:

    ```sh
    python -m venv venv
    source venv/bin/activate
    ```

3. Instala las dependencias:

    ```sh
    pip install -r requirements.txt
    ```

4. Configura la base de datos:

    ```sh
    python manage.py migrate
    ```

5. Carga datos de prueba (opcional):

    ```sh
    python manage.py loaddata initial_data.json
    ```

6. Ejecuta el servidor de desarrollo:

    ```sh
    python manage.py runserver
    ```

7. Accede a la aplicación en tu navegador:

    ```
    http://127.0.0.1:8000
     ```
   ## Contribuir
Si deseas contribuir a este proyecto, sigue los siguientes pasos:

1. Haz un fork del repositorio.sh
2. Crea una nueva rama (git checkout -b feature-nueva-funcionalidad).
3. Realiza tus cambios y haz commit (git commit -am 'Añade nueva funcionalidad').
4.  Sube tu rama (git push origin feature-nueva-funcionalidad).
5. Crea un nuevo Pull Request

## Hecho por:

-`Lautaro Palacios.`
