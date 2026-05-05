# ☕ cafe_site – Online Coffee Shop

A full-featured web application for an online café where users can browse the menu, create accounts, add items to their cart, and place orders. Built with Django.

## ✨ Features

- Browse café menu with categories
- User registration and login
- Add products to shopping cart
- Place and track orders
- Admin panel (Django default) for managing products and orders

## 🛠️ Technologies Used

- Python 3 & Django (Backend)
- HTML5, CSS3 (Frontend)
- SQLite (Database)
- Bootstrap (Responsive design)

## 🚀 Installation & Setup

Clone the repository:
--------------------------------
git clone https://github.com/newsha-adib/cafe_site.git
cd cafe_site

Create and activate virtual environment:
----------------------------------------
python -m venv venv

Linux / Mac:
source venv/bin/activate

Windows:
venv\Scripts\activate

Install dependencies:
---------------------
pip install -r requirements.txt

Apply migrations:
-----------------
python manage.py migrate

Run development server:
-----------------------
python manage.py runserver

Open in browser:
----------------
http://127.0.0.1:8000

## 👩‍💻 Project Structure

cafe_site/
│
├── cafe/          # Main app for café and menu management
├── accounts/      # User registration and login
├── orders/        # Shopping cart and order handling
├── templates/     # HTML templates
├── static/        # CSS, JS, images
├── media/         # Uploaded product images
│
├── manage.py
├── requirements.txt
└── db.sqlite3     # Local development database


## 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.


## 🤝 Contributing
Suggestions and improvements are welcome.  
Feel free to open an Issue or submit a Pull Request.


## 📧 Contact

Developer: Newsha Adib  
GitHub: https://github.com/newsha-adib


This project was developed as a practice project to improve Django and full‑stack web development skills.
