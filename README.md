# Django Tutorial – Urnau Leonardo

Este repositorio contiene el resultado del tutorial oficial de Django, implementado paso a paso. El proyecto incluye una aplicación de encuestas (`polls`) dentro del proyecto principal (`mysite`), ideal para quienes están comenzando con Django y desean comprender su estructura y flujo de trabajo.

## 📚 Descripción

El objetivo de este proyecto es seguir el tutorial oficial de Django para construir una aplicación web básica que permita:

- Crear y gestionar encuestas.
- Votar en tiempo real.
- Visualizar resultados de forma dinámica.
- Administrar contenido desde el panel de administración de Django.

## 🛠️ Tecnologías utilizadas

- **Python**: 3.x
- **Django**: 5.x (o la versión más reciente compatible)
- **Base de datos**: SQLite (por defecto)
- **Frontend**: HTML + CSS básico

## 🚀 Instalación y ejecución local

1. **Clonar el repositorio**

   ```bash
   git clone https://github.com/redbreake/django-tutorial.git
   cd django-tutorial
   ```

2. **Crear y activar un entorno virtual**

   ```bash
   python -m venv env
   source env/bin/activate  # En Windows: env\Scripts\activate
   ```

3. **Instalar dependencias**

   ```bash
   pip install django
   ```

4. **Aplicar migraciones y ejecutar el servidor**

   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

5. **Acceder a la aplicación**

   Abre tu navegador y visita: [http://localhost:8000/polls/](http://localhost:8000/polls/)

## 🧪 Estructura del proyecto

```
mysite/
├── manage.py
├── mysite/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── polls/
    ├── admin.py
    ├── apps.py
    ├── migrations/
    ├── models.py
    ├── templates/
    ├── tests.py
    └── views.py
```

## 📄 Licencia

Este proyecto es una implementación del tutorial oficial de Django y se proporciona con fines educativos. Puedes utilizarlo y modificarlo libremente según tus necesidades.
