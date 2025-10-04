# 📚 Library Management System API

This project is a **Django + Django REST Framework API** for managing library resources.
It provides endpoints for managing books, users, and transactions such as borrowing and returning books.

---

## 🚀 Features

* **Books Management (CRUD)**: Add, view, update, and delete books.
* **Users Management (CRUD)**: Manage library members.
* **Borrow & Return Books**: Users can check out and return books, with availability automatically updated.
* **View Available Books**: List all available books with search by title, author, or ISBN.
* **Authentication**: Basic user authentication with Django’s built-in system.

---

## 🛠️ Tech Stack

* **Backend**: Django, Django REST Framework
* **Database**: SQLite (default, easy setup)
* **Deployment**: Heroku / PythonAnywhere (planned)

---

## 📂 Project Structure

```
Library-Management-System-API/
│
├── library_api/        # Django project settings
├── library/            # Main app (models, views, serializers, urls)
├── manage.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/Library-Management-System-API.git
   cd Library-Management-System-API
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate      # Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:

   ```bash
   python manage.py migrate
   ```

5. Start the development server:

   ```bash
   python manage.py runserver
   ```

---

## 🔮 Next Steps

* Add JWT authentication for secure access.
* Implement user roles (Admin, Member).
* Deploy API online (Heroku/PythonAnywhere).

---

## 👤 Author

Kelcy Kipngok
Frontend + Backend Developer in training 🚀
