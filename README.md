# DjangoAuthFlow
 DjangoAuthFlow: My journey learning Django authentication. A clean, modern implementation featuring user registration, login/logout, protected views, and responsive UI. Built while exploring Django's auth system. Feedback welcome! ✨ #Django #LearningJourney

===========================================
DJANGO AUTHENTICATION PROJECT SETUP
===========================================

Project Name: DjangoAuthFlow

GitHub Repository Structure:
----------------------------
DjangoAuthFlow/
├── authApp/
│   ├── templates/accounts/
│   │   ├── login.html
│   │   ├── logout.html
│   │   ├── register.html
│   │   ├── home.html
│   │   └── protected.html
│   ├── static/styles/
│   │   └── styles.css
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── authProject/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
├── requirements.txt
└── README.md

===========================================
README.md CONTENT (copy to README.md file)
===========================================

# DjangoAuthFlow 🔐

A clean, modern authentication system built with Django featuring:
- User registration with password validation
- Login/logout functionality
- Protected views
- Responsive UI with elegant styling
- Session management

## Features ✨
- Custom registration form with password confirmation
- Login error handling
- Protected route using Django's `LoginRequiredMixin`
- CSRF protection
- Mobile-responsive design
- Blue & white theme with smooth interactions

## Screenshots 📸

https://github.com/iamohammed1/DjangoAuthFlow/blob/main/log-in.png?raw=true
https://github.com/iamohammed1/DjangoAuthFlow/blob/main/home.png?raw=true


## Installation ⚙️
1. Clone repository:
```bash
git clone https://github.com/iamohammed1/DjangoAuthFlow.git
cd DjangoAuthFlow
