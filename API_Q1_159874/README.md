E-Commerce Django Project

This is a Django-based e-commerce project with `Customer` and `Order` models. The project allows customers to place orders, with a one-to-many relationship between customers and orders.

Follow these steps to set up the development environment for the Django project:

# Create a virtual environment:
python -m venv .venv
# Activate the virtual environment:
.\.venv\Scripts\Activate.ps1
# Install Django using pip:
pip install django
# Create a project:
django-admin startproject Ecommerceproject
# Navigate to the project folder:
cd Ecommerceproject
# Create a superuser
python manage.py createsuperuser
# Create Migrations for models.py:
python manage.py makemigrations
python manage.py migrate
# Run the Development Server:
python manage.py runserver
# Go to admin website:
http://127.0.0.1:8000/admin/
