<h1 align="center">Django Social Media Site</h1>

<p align="center">
  🚀 A mini Instagram-style platform built using Django, where the admin can post photos, and users can view them on the homepage.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/🌐 Framework-Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/🐍 Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/🎨 Frontend-HTML%2FCSS%2FJS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>


---

> 🎯 *Homepage with post feed (Replace this GIF with your own preview once available).*

---

## 🔧 Tech Stack

- 🎨 Frontend: HTML, CSS, JavaScript (with Bootstrap)
- 🧠 Backend: Python & Django
- 🛠️ Admin Dashboard: Django's built-in admin interface

---

## 📦 Features

- 👨‍💼 Admin can add posts (image, username, caption)
- 🖼️ Users can view all uploaded posts
- 📁 Media file upload handling
- 🎨 Clean and minimal design
- 💻 100% Responsive Layout (Bootstrap)

---

## 🚀 Getting Started

### Clone the Repo

```bash
git clone https://github.com/UpendraPrawal/Social-Media-Site-.git
cd Social-Media-Site-
````

### Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### Install Requirements

```bash
pip install -r requirements.txt
```

Or install Django manually:

```bash
pip install django
```

### Apply Migrations

```bash
python manage.py migrate
```

### Create Admin User

```bash
python manage.py createsuperuser
```

### Run the Server

```bash
python manage.py runserver
```

Open your browser:

* 🌍 `http://127.0.0.1:8000` — Homepage
* 🔒 `http://127.0.0.1:8000/admin` — Admin Dashboard

---

## 🗂️ Project Structure

```
Social-Media-Site-/
├── media/                  # Uploaded images
├── static/                 # Static files (CSS/JS)
├── templates/              # HTML templates
├── posts/                  # App folder (models/views/admin)
├── social_media_site/      # Main project folder
├── db.sqlite3              # Database file
├── manage.py               # Django CLI
└── README.md
```

---

## 🔮 Future Upgrades

* 🔐 User login/signup and authentication
* 💬 Commenting & liking system
* 🔎 Search posts by user/caption
* 🌍 Deployment on Render/Heroku
* 📱 PWA / Mobile optimization

---

## 🙋‍♂️ Author

Made with ❤️ by [Upendra Prawal](https://github.com/UpendraPrawal) & [Harshit Upadhyay](https://github.com/harshit008-upadhyay)


---
