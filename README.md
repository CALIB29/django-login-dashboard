# Django Login and Dashboard System

A fully functional web application with user authentication, dashboard, and CRUD operations built using Django.

## Features

- User Authentication (Login/Logout)
- Dashboard View
- CRUD Operations for Items
- Responsive UI using Bootstrap
- Form Validation
- Flash Messages

## Setup

1. Clone the repository:
```bash
git clone <your-repo-url>
cd raph
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/Scripts/activate  # On Windows
source venv/bin/activate      # On Unix or MacOS
```

3. Install dependencies:
```bash
pip install django
```

4. Apply migrations:
```bash
python manage.py migrate
```

5. Create a superuser:
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000/ and login with your superuser credentials.

## Project Structure

- `main/` - Main application directory
  - `templates/` - HTML templates
  - `models.py` - Database models
  - `views.py` - View functions
  - `urls.py` - URL configurations
  - `forms.py` - Form definitions

## License

MIT License