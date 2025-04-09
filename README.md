# 📝 Flask Blog Platform

A fully functional, customizable blog platform built with a full-stack Flask framework. This app enables users to create accounts, write and manage blog posts, comment on content, and explore a sleek, dynamic frontend.

## 🚀 Features

- 🧑 User Registration & Authentication (hashed passwords using `werkzeug.security`)
- 📝 Create, Read, Update, Delete (CRUD) for blog posts
- 💬 Commenting system (only for logged-in users)
- 🔐 Admin-only content management routes
- 📆 Posts timestamped with automatic date creation
- 📸 User avatars via Gravatar
- 📦 Resettable SQLite database for development

## ⚙️ Tech Stack

### Backend

- **Flask** – Lightweight Python web framework
- **Flask-Login** – User session and login management
- **Flask-Bootstrap5** – Frontend integration
- **Flask-CKEditor** – Rich text editing for blog posts
- **SQLAlchemy** – ORM for database models
- **Flask-Gravatar** – User avatar generation
- **SQLite** – Lightweight, file-based database
- **Python dotenv** – Environment variable management

### Frontend

- HTML views rendered with bootstrap and jinja2
- Bootstrap 5 styling

## 🧩 High Customizability

This application is designed to be highly extensible:
- Swap out SQLite for any relational database supported by SQLAlchemy
- Update templates to customize the UI experience
- Add routes for tags, categories, or likes
- Enhance security features with 2FA or OAuth integrations

## 🛠 Setup

1. Clone the repository
2. Create a virtual environment and install dependencies:
   ```bash
   pip install -r requirements.txt

Set up a .env file with your FLASK_SECRET_KEY

Run the application:
python app.py

## File structure:

project/
│
├── templates/              # HTML views
├── static/                 # Static assets (CSS, JS, images)
├── forms.py                # WTForms-based forms
├── app.py                  # Main Flask application
├── requirements.txt        # Dependencies
└── README.md

## 📌 Development Note

A /reset_db route is available for development purposes to reset the database with one click (should be removed before production deployment).

Feel free to modify and extend this project for your own needs! Contributions welcome.

## 💖 Final Thoughts

Thank you for checking out this project! Whether you're learning Flask, building your own blog, or just exploring new codebases — I hope this app inspires you to create and customize something amazing.

If you find this project helpful or fun to work with, feel free to ⭐️ star the repo, share feedback, or contribute improvements. Your support means the world!

Happy coding and keep building awesome things! 🚀💡

— With gratitude,  
Milos Grujic aka Gruyanidas
