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

### Prerequisites

- Python 3.8+  
- Django 4.x  
- Git

### Steps

1. **Clone the repository**

git clone https://github.com/Sanjay2012/django-auth-demo.git
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

Contributing
Contributions are welcome!
1. Fork the repository
2. Create a new branch: 
  > git checkout -b feature/your-feature
3. Commit your changes: 
  > git commit -m "Add your feature"
4. Push to the branch: 
  > git push origin feature/your-feature
5. Open a Pull Request