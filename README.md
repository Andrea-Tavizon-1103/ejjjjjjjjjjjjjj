# ejjjjjjjjjjjjjj
- 1 Crear carpeta de trabajo Accestel1103
- 2 Abrir con vs code la carpeta
- 3 Abrir terminal de vs code
- 4 Verificar que esta python y su version en terminal
- 5 link vs code Django --> https://code.visualstudio.com/docs/python/tutorial-django
- 6 Crear el entorno de trabajo --> python -m venv .venv
- 7 Activar el entorno --> .venv\scripts\activate.bat
- 8 Seleccionar interprete de python --> Precione F1
- 9 Actualizar pip --> python -m pip install --upgrade pip
- 10 Instalar Django --> python -m pip install django
- 11 Creando el proyecto --> django-admin startproject backend .
- 12 Realizar migracion al preoyecto --> python manage.py migrate
- 13 Ejecutar servidor --> python manage.py runserver
- 14 python manage.py startapp accesorios_app
- 15 settings backend 'accesorios_app',
- 16 base de datos DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': 'accesorios.db',
    }
}
- 17 migrate
- 18 urls
- 
