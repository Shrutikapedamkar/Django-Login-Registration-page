# Django Login and Registration Page

This is a simple login and registration page built using Django and Python. It allows users to create accounts and log in.

Navigate to the project directory:
```bash
cd django-login-registration
```

Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

Install the project dependencies:
```bash
pip install -r requirements.txt
```

Apply the database migrations:

```bash
python manage.py migrate
```

Create a superuser account:
```bash
python manage.py createsuperuser
```
Start the development server:
```bash
python manage.py runserver
```
Open your web browser and navigate to http://localhost:8000/ to access the login and registration page.

