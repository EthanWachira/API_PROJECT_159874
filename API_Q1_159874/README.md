E-Commerce Django Project

This is a Django-based e-commerce project with `Customer` and `Order` models. The project allows customers to place orders, with a one-to-many relationship between customers and orders.

Follow these steps to set up the development environment and run the Django project:

# Create a virtual environment:
python -m venv .venv
# Activate the virtual environment:
.venv/Scripts/activate
# Install Django:
pip install django
# Create a project:
django-admin startproject Ecommerceproject
# Go to project directory:
cd Ecommerceproject
# Create Migrations for models.py:
python manage.py makemigrations
python manage.py migrate
# Create a superuser:
python manage.py createsuperuser
# Run the Development Server:
python manage.py runserver
# Access the admin website:
http://127.0.0.1:8000/admin
