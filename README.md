# Python Full Stack E-Commerce Application

## 📌 Project Overview
This project is a full-stack E-commerce web application developed using Python and Django. It provides an online shopping platform where users can browse products, manage their shopping experience, and make secure online payments through Razorpay integration.

The project also uses the Django Admin Panel to manage products, orders, and other application data efficiently.

## 🚀 Features
- **Product Management:** Manage and display products.
- **Django Admin Panel:** Manage products, users, orders, and application data.
- **Online Payment Integration:** Integrated Razorpay payment gateway for online transactions.
- **E-Commerce Functionality:** Supports the core features of an online shopping application.
- **Backend Development:** Built using Python and Django.
- **Full-Stack Architecture:** Combines frontend interfaces with backend business logic and database operations.

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Backend Framework:** Django
- **Administration:** Django Admin
- **Payment Gateway:** Razorpay
- **Frontend:** HTML, CSS, JavaScript *(if used in your project)*
- **Database:** SQLite / MySQL / PostgreSQL *(specify the database you used)*

## ⚙️ Installation and Setup

### 1. Clone the Repository
```bash
git clone <your-repository-url>
cd <project-folder>
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```

Activate the environment:

**Windows**
```bash
venv\Scripts\activate
```

**Linux / macOS**
```bash
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply Database Migrations
```bash
python manage.py migrate
```

### 5. Create a Superuser
```bash
python manage.py createsuperuser
```

### 6. Run the Development Server
```bash
python manage.py runserver
```

Open the application at:

http://127.0.0.1:8000/

Access the Django Admin Panel at:

http://127.0.0.1:8000/admin/

## 💳 Razorpay Payment Integration
The application integrates the Razorpay payment gateway to facilitate online payments.

For security, configure your Razorpay API credentials using environment variables rather than hardcoding secret keys in the source code.

## 🎯 Project Objective
The objective of this project is to develop a practical full-stack web application using Python and Django while implementing e-commerce functionality, administrative management, and online payment integration.

## 👨‍💻 Author
**Shailendra Rai**

Python Full Stack Developer
