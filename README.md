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
log in
![image alt](https://github.com/iamohammed1/DjangoAuthFlow/blob/3d27b57c408484e758c08d0b2ba7498f4fcb42a2/log-in.png)
home
![image alt](https://github.com/iamohammed1/DjangoAuthFlow/blob/dacec52db2e03fda6227ee0b7b25ca11d6013e8d/home.png)


## Installation ⚙️
1. Clone repository:
```bash
git clone https://github.com/iamohammed1/DjangoAuthFlow.git
cd DjangoAuthFlow
