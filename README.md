 MyTodo — Flask Todo App

A simple and clean Todo List Web Application built with Flask and Bootstrap 5, backed by SQLite via SQLAlchemy.

 Features

 ✅ Add new todos with a title and description
 📋 View all todos in a clean table layout
 ✏️ Update existing todos
 🗑️ Delete todos
 📅 Auto-generated timestamps for each todo
 📱 Fully responsive with Bootstrap 5
 ⚠️ Empty state message when no todos exist


## 🛠️ Tech Stack

| Layer | Technology |

| Backend | Python, Flask |
| Database | SQLite + SQLAlchemy |
| Frontend | HTML, Bootstrap 5 |
| Templating | Jinja2 |

## 🚀 Getting Started Locally

### 1. Clone the repository
git clone https://github.com/meerqamar/flask_todoApp.git
cd flask_todoApp

### 2. Create a virtual environment
python -m venv env
source env/bin/activate       # Mac/Linux
env\Scripts\activate          # Windows

### 3. Install dependencies
pip install -r requirements.txt

### 4. Run the app
python app.py

Visit 👉 
https://flask-todo-app-sigma.vercel.app/
---

## 📁 Project Structure

├── static/
│   ├── test.js
│   ├── style.css   
├── templates/
│   ├── base.html
│   ├── index.html
│   └── update.html
├── instance/
│   └── todo.db
├── app.py
├── requirements.txt
└── README.md

---

## 📄 License

This project is open source and available under the MIT License.
