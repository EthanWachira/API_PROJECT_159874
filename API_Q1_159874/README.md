E-Commerce Django Project

This is a Django-based e-commerce project with `Customer` and `Order` models. The project allows customers to place orders, with a one-to-many relationship between customers and orders.

Follow these steps to set up the development environment for the Django project:

# Create a virtual environment:
python -m venv .venv
# Activate the virtual environment:
.\.venv\Scripts\Activate.ps1
# Start the Develoment Server:
python manage.py runserver

Follow these steps to set up the run the Django project:
# Create Migrations for models.py:
python manage.py makemigrations
python manage.py migrate
# Run the Development Server:
python manage.py runserver