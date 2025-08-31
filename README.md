# Django Auth Demo 🚀

**Author:** Sanjay Waware  
**Email:** <sanjaywaware04@gmail.com>  
**GitHub:** https://github.com/Sanjay2012/ 


A simple Django project demonstrating **user authentication** (registration, login, and logout) with secure logout handling using POST requests. This project is ideal for beginners to understand Django's built-in authentication system.

---

## Table of Contents

- [Features](#features)  
- [Demo Screenshots](#demo-screenshots)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Security Notes](#security-notes)  
- [Contributing](#contributing)  
- [License](#license)

---

## Features

- User registration with form validation  
- User login and logout functionality  
- Secure logout using POST method with CSRF protection  
- Conditional rendering for authenticated and unauthenticated users  
- Clean template structure using Django template inheritance

---

## Demo Screenshots

*(Optional: Add screenshots of your login page, home page, and registration page here.)*

---

## Installation

### Prerequisites

- Python 3.8+  
- Django 4.x  
- Git

### Steps

1. **Clone the repository**

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
Create a virtual environment

python -m venv env
Activate the virtual environment

Windows:
env\Scripts\activate

Mac/Linux:
source env/bin/activate


Install dependencies
pip install -r requirements.txt

Apply migrations
python manage.py migrate

Run the development server
python manage.py runserver
Open http://127.0.0.1:8000/ in your browser.

Usage
Navigate to the Home Page

If logged in, you’ll see a welcome message with a secure logout button.

If not logged in, links to Login and Register pages are shown.

Register a new user

Fill in the registration form and submit.

Login

Enter your username and password to log in.

Logout

Click the Logout ✅ button to securely log out using a POST request.

Project Structure
pgsql
Copy code
django-auth-demo/
├── manage.py
├── <app_name>/
│   ├── migrations/
│   ├── templates/
│   │   ├── base.html
│   │   ├── index.html
│   │   ├── login.html
│   │   └── register.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
├── db.sqlite3
├── requirements.txt
└── .gitignore
Security Notes
Logout uses POST requests with CSRF tokens for security.

Do not commit your .env file with sensitive information like SECRET_KEY.

Database (db.sqlite3) is ignored in .gitignore.

Contributing
Contributions are welcome!

Fork the repository

Create a new branch: git checkout -b feature/your-feature

Commit your changes: git commit -m "Add your feature"

Push to the branch: git push origin feature/your-feature

Open a Pull Request