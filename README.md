# 📚 Library Inventory RESTful API

This is a simple RESTful API for managing a library system using Flask.

## 🚀 Features

- Add books
- View all books
- View single book
- Update book
- Delete book

## 📁 Endpoints

| Method | Endpoint      | Description          |
|--------|---------------|----------------------|
| POST   | `/books`      | Add a new book       |
| GET    | `/books`      | Get all books        |
| GET    | `/books/<id>` | Get book by ID       |
| PUT    | `/books/<id>` | Update book by ID    |
| DELETE | `/books/<id>` | Delete book by ID    |

## 🛠️ Setup

```bash
pip install -r requirements.txt
python app.py
