 📚 CampusConnect: A Django Web App for Student Profiles and Authentication

CampusConnect is a Django-powered web application that allows university students to register, log in, update their profiles, and manage academic details like course and semester. Designed to be beginner-friendly, this project is perfect for understanding Django's core components such as models, forms, user authentication, and media handling.

---
 🔧 Features

* ✅ User registration & login/logout
* 👤 Profile creation with course, semester, bio, and profile picture
* 🔒 Authentication using Django's built-in user system
* 📂 Media file upload support (profile pics)
* 🖥️ Admin panel access for managing users and profiles

---

🏗️ Tech Stack

* **Backend**: Django 5.2.3
* **Frontend**: HTML (Django templates)
* **Database**: SQLite3
* **Image Handling**: Pillow (Python imaging library)
* **Deployment Ready**: GitHub + Render/Heroku friendly structure

---

🚀 Getting Started (Local Setup)

🔁 Clone the repo:

```bash
git clone https://github.com/ManasviSingh01/CampusConnect-A-Django-Web-App-for-Student-Profiles-and-Authentication.git
cd CampusConnect-A-Django-Web-App-for-Student-Profiles-and-Authentication
```

🐍 Create virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 📦 Install dependencies:

```bash
pip install -r requirements.txt
```

### ⚙️ Apply migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

### 👑 Create superuser:

```bash
python manage.py createsuperuser
```

### ▶️ Run the server:

```bash
python manage.py runserver
```

Visit: `http://127.0.0.1:8000/`

---

## 🗂️ Project Structure

```
├── manage.py
├── requirements.txt
├── .gitignore
├── README.md
├── campusconnect/        # Project settings
├── users/                # Django app with models, views, urls
├── templates/            # HTML templates
├── static/               # Static files (CSS/JS)
└── media/                # User-uploaded files
```

---

## 🖼️ Screenshots (optional)

Add screenshots here if needed for presentation.

