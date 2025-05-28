# 📝 Notes App

A simple, secure web-based notes app built using **Flask**, **MySQL**, **Flask-Login**, and **SQLAlchemy**.

---

## 📁 Project Structure

website/

├── static/

│ └── index.js # JavaScript (optional UI enhancements)

│

├── templates/

│ ├── base.html # Common layout template

│ ├── home.html # Notes dashboard

│ ├── login.html # Login page

│ └── signup.html # Signup page

│

├── init.py # App factory and configuration

├── auth.py # Auth routes (login/register)

├── views.py # Core app routes (home, notes)

├── models.py # SQLAlchemy models

├── requirements.txt # Python dependencies

└── README.md # You're here!

---

## ⚙️ Features

- User registration & login with session management
- Add and delete personal notes
- MySQL database integration
- Responsive templates with Flask and Jinja2

---

## 🧪 Local Setup Instructions

### 1. Clone the Repository

```
git clone https://github.com/yourusername/flask-notes-app.git
cd flask-notes-app/website
```
2. Set Up Virtual Environment
```
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
```
3. Install Dependencies
```
pip install -r requirements.txt
```
4. Set Up Your MySQL Database
Start MySQL server

Create a database:

sql
```
CREATE DATABASE notes;
```
Make sure your credentials match your MySQL setup.

🚀 Running the App Locally
From the website/ folder:
```
python -m flask run
```

Then, visit: http://127.0.0.1:5000/

On the first run, it will create all necessary database tables automatically.

📦 requirements.txt (Sample)
```
Flask
Flask-Login
Flask-SQLAlchemy
```

Snippets:
User Login
![1](https://github.com/user-attachments/assets/7c085ce0-ce2b-4124-8c96-5331fff52ebb)
User Registration
![2](https://github.com/user-attachments/assets/40aa1677-8c2a-4eb2-8ffd-3579b5cf9519)
Add Notes
![4](https://github.com/user-attachments/assets/114f2a61-8760-4db9-b5d4-27cbee4c210f)
Delete Notes
![5](https://github.com/user-attachments/assets/5ee71264-e391-468a-b2c6-13ed6e0ffbe0)











