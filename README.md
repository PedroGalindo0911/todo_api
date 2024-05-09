## Backend de Aplicación de Gestión de Tareas

Este proyecto contiene el backend de una aplicación web diseñada para gestionar tareas. El backend está desarrollado utilizando Django y se conecta a una base de datos MySQL para almacenar y recuperar datos relacionados con las tareas.

### Instrucciones para Ejecutar

**1. Clona el Repositorio**

git clone https://github.com/tu-usuario/todo_api.git

**2. Instala las Dependencias**

Navega hasta el directorio del backend y crea un entorno virtual (si es necesario):

cd todo_api
python -m venv venv
source venv/bin/activate  # Para Linux/macOS
venv\Scripts\activate      # Para Windows
pip install -r requirements.txt

**3. Configura la Base de Datos**

- Crea una base de datos MySQL en tu entorno local.
- Configura las credenciales de la base de datos en el archivo `settings.py` del proyecto Django.

**4. Ejecuta las Migraciones**

Ejecuta las migraciones para configurar la estructura inicial de la base de datos:

python manage.py migrate

**5. Inicia el Servidor Django**

Ejecuta el siguiente comando para iniciar el servidor de desarrollo de Django:

python manage.py runserver

Esto iniciará el servidor de backend en http://localhost:8000.

### Estructura de Archivos

- backend/ : Contiene los archivos fuente del backend Django.
  - tasks/ : Aplicación Django para gestionar las tareas.
  - manage.py : Punto de entrada principal para ejecutar comandos de Django.
  - settings.py : Configuración del proyecto Django.

### Tecnologías Utilizadas

- Django (Framework web para Python)
- MySQL (Base de datos relacional)

---

**NOTA**: Este backend proporciona la API necesaria para interactuar con la base de datos y completar la funcionalidad de la aplicación de gestión de tareas desarrollada en el frontend (link del repo del frontend: https://github.com/PedroGalindo0911/todo-app).
