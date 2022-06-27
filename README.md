Se realizaron 3 PUSH:

Se crearon 3 brenches diferentes, la entrega final la pagina/Blog completo se encinetra en  breanch mainFinal  ###!!!importante!!!!!


Paso N°1:

Antes de Inciar el Servidor, tener los siguentes pip instalados:

  Django 2.2.7 : pip install Django==2.2.7
  django-crispy-forms : pip install django-crispy-forms
  Pillow : pip install Pillow

<!--------------------------------------------------------------------------------->
Paso N°2:

Crear superuser para ingresar a la base de datos admin:
Utilizar el comando:

    python manage.py createsuperuser

<!--------------------------------------------------------------------------------->
Paso N°3:

Solo realizar si estan los pip instalados; Uso:

   (Encontrarse en la misma carpeta de manage.py y realizar los siguientes comandos)

    python manage.py makemigrations

    python manage.py migrate

    python manage.py runserver
    
  Se abrira el servidor del blog: http://127.0.0.1:8000/



