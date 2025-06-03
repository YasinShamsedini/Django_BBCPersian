# 📰 Django BBC Persian – News Publishing Platform

A modern news website built with Django, designed for dynamic content delivery and category-based article management. This project is a functional prototype inspired by the structure of professional media platforms.

---

## 🚀 Features

- Full Django backend with SQLite database
- Multi-app structure for clean separation (news, UI, etc.)
- Template-based layout with reusable components (`base.html`)
- Admin panel for content management
- Dynamic article rendering with multilingual support (Persian-focused)
- Deployed to [Render](https://render.com)
- Asked ChatGPT to help in provinding real-world content for the pages(Content + HTML + CSS)

---

## 🛠️ Tech Stack

- **Backend:** Django 5.2
- **Database:** SQLite (default)
- **Production:** Gunicorn + Render.com
- **Frontend:** HTML, CSS, Django Templates

---

## 🌐 Demo Images

![Category]([screenshots/homepage.png](https://github.com/YasinShamsedini/Django_BBCPersian/blob/main/Sample%20Category.png))

---

## 📦 Installation

To run the project locally:

```bash
git clone https://github.com/YOUR_USERNAME/Django_BBC_Persian.git
cd Django_BBC_Persian
python -m venv venv
source venv/bin/activate  # Or: venv\Scripts\activate (on Windows)
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
