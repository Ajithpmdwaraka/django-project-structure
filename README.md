# Django Project Structure Template

This repository provides a well-organized and scalable project structure for Django applications. Use this template to kickstart your Django projects with a clean and modular layout, following best practices.

---

## 📂 Project Structure

The structure of the project is as follows:

```plaintext
django-project-structure/
├── manage.py            # Django's command-line utility
├── requirements.txt     # Python dependencies
├── .env.example         # Example environment configuration file
├── .gitignore           # Ignored files and folders in Git
├── config/              # Main configuration directory
│   ├── __init__.py
│   ├── settings/        # Modularized settings
│   │   ├── __init__.py
│   │   ├── base.py      # Base settings
│   │   ├── dev.py       # Development settings
│   │   ├── prod.py      # Production settings
│   ├── urls.py          # Project-level URL routing
│   ├── wsgi.py          # WSGI application
│   └── asgi.py          # ASGI application
├── apps/                # All Django apps
│   ├── core/            # Example app for core functionalities
│   │   ├── migrations/  # Database migrations
│   │   ├── admin.py     # Admin configurations
│   │   ├── apps.py      # App configurations
│   │   ├── models.py    # Database models
│   │   ├── tests.py     # Unit tests
│   │   └── views.py     # Business logic
│   └── __init__.py
├── static/              # Static files (CSS, JS, images)
├── templates/           # HTML templates
└── docs/                # Documentation for the project
