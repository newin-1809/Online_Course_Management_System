# 📘 Online Learning Platform

A Django-based Online Learning Platform where students can enroll in courses, instructors can manage content, and administrators can control the system efficiently.

---

## 🚀 Features

- 👨‍🎓 Student Registration & Login (JWT Authentication)
- 👨‍🏫 Instructor Management
- 📚 Course Creation & Enrollment
- 🔍 Search & Filter Courses
- 🛠 Admin Dashboard
- 🗄 PostgreSQL Database Integration
- 🔐 Secure Authentication System
- ⚡ REST API using Django Rest Framework

---

## 🛠 Tech Stack

- Python
- Django
- Django Rest Framework
- PostgreSQL
- JWT Authentication
- Redis (if implemented)
- Git & GitHub

---

## 📂 Project Structure


online_learning_platform/
│
├── accounts/ # User & authentication management
├── courses/ # Course & enrollment logic
├── manage.py
├── requirements.txt
└── README.md


---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository


git clone https://github.com/YOUR_USERNAME/online-learning-platform.git
cd online-learning-platform
2️⃣ Create Virtual Environment
python -m venv env

Activate:

env\Scripts\activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Configure Database

Update settings.py with your PostgreSQL credentials:

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'your_db_name',
        'USER': 'your_username',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
5️⃣ Apply Migrations
python manage.py makemigrations
python manage.py migrate
6️⃣ Run Server
python manage.py runserver

Server will run at:

http://127.0.0.1:8000/
🔐 Authentication

This project uses JWT (JSON Web Token) for secure authentication.

Obtain Token:
POST /api/token/
Refresh Token:
POST /api/token/refresh/
📌 Future Improvements

Payment Integration

Video Course Upload

Deployment on Cloud (Render / AWS)

Email Verification

Course Reviews & Ratings

👤 Author

Newin
Django Backend Developer

⭐ Contribute

If you like this project, give it a ⭐ on GitHub!

```bash