# LittleLemonProject

Little Lemon Project
Title: the Little Lemon Django project
Little Lemon is a full stack Python and Django database driven web application. The app follows MVT architecture design. Developed a database that allows clients to do booking and order menus from HTTP clients, web browsers. Web master, administrator, can login into the admin page, view, edit make other changes to the client requests, booking and menus.
Installation:
python -m pip install Django
Setup PostgreSQL database and create a database in your environment:
DATABASES = { 'default': { 'ENGINE': 'django.db.backends.postgresql', 'NAME': ‘database_name’, 'USER': ‘username’, 'PASSWORD': ‘password_for_username’, 'HOST': ‘hostname_or_ip_address ’ , 'PORT': ‘port’\_number, } }
Usage:

Open a Terminal window

Start the development server
Python manage.py run server (optional port number) Default Port 8000

Click on the URL on the terminal
http://127.0.0.1:8000/

- Accessing the Admin page

# Create a new superuser with a password

python manage.py createsuperuser

# Visit the admin page

http://127.0.0.1/admin

# Create a new Menu - Menu items and details

Click “Menu” or “+ Add”

# Click “ADD Add Menu +” and add the details

    - Name:
    - Price:
    - Description :

# Click “SAVE” and visit http://127.0.0.1:8000/menu to see the menu.
