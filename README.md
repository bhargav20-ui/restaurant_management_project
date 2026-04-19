# 🍽️ Restaurant Management System

A **Django-based Restaurant Management System** that helps manage products, orders, and user accounts efficiently. This project is built as part of an internship learning experience to understand real-world backend development using Django and Django REST Framework.

---

## 🚀 Features

* 🔐 User Authentication (Login/Register)
* 📦 Product Management (Add, Update, Delete, View)
* 🛒 Order Management System
* 🏠 Home Dashboard
* 🔄 REST API support using Django REST Framework
* 📄 CRUD Operations for different modules

---

## 🛠️ Tech Stack

* **Backend:** Python, Django, Django REST Framework
* **Database:** SQLite (default)
* **Version Control:** Git & GitHub

---

## 📁 Project Structure

```
restaurant_management_project/
│── account/        # User authentication & profiles
│── home/           # Dashboard / home logic
│── orders/         # Order management
│── products/       # Product management
│── restaurant_management/  # Main project settings
│── manage.py
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/bhargav20-ui/restaurant_management_project.git
cd restaurant_management_project
```

2. Create a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate   # On Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Apply migrations:

```bash
python manage.py migrate
```

5. Run the server:

```bash
python manage.py runserver
```

---

## 🌐 API Endpoints

* `/api/products/` → Manage products
* `/api/orders/` → Manage orders
* `/api/account/` → User-related operations

---

## 📌 Future Improvements

* 💳 Payment Integration
* 📊 Admin Dashboard with Analytics
* 📱 Frontend Integration (React / Flutter)
* 📦 Order Tracking System

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is for educational purposes and does not currently use a specific license.

---

## 👨‍💻 Author

**Vinay Venkata Bhargav**
Engineering Student | Django Developer

---

⭐ If you like this project, don't forget to give it a star!
