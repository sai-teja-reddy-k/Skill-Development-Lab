Django CRUD App – SDC Lab Experiment 16
A clean and functional CRUD-based web application built using Django, developed as part of the Skill Development Course (SDC) Lab – Experiment 16.

🌟 Features
🧾 Create, Read, Update, and Delete (CRUD) records

🎨 Modern interface using Django templates

🔐 Built-in CSRF protection on all forms

🗃️ Data managed with SQLite

💡 Modular, scalable code design

📸 Screenshots
📋 Home Page / List View

➕ Create / Add Record

📝 Edit / Update Record

❌ Delete Record

💡 Save your screenshots in the screenshots/ folder.

🚀 Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/django-sdc-crud.git
cd django-sdc-crud
Create a virtual environment

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate  # For Windows
Install dependencies

bash
Copy
Edit
pip install django
Run migrations

bash
Copy
Edit
python manage.py makemigrations
python manage.py migrate
Start development server

bash
Copy
Edit
python manage.py runserver
Open in browser

text
Copy
Edit
http://127.0.0.1:8000/
🗂️ Project Structure
pgsql
Copy
Edit
django_sdc_crud/
├── main_app/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
│       └── main_app/
│           ├── index.html
│           ├── create.html
│           ├── update.html
├── static/
│   └── css/
│       └── style.css
├── db.sqlite3
├── manage.py
├── requirements.txt
🧠 Concepts Used
Django Views & Models

Django Forms

Template Inheritance

SQLite Integration

Static and Media Files Management

Created with  by Sai Teja Reddy
GitHub
