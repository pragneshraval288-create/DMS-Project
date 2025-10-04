DMS Project (Document Management System) 🚀

Overview

DMS Project is a Document Management System where users can register, login, reset password, and manage documents.  
It is built using Flask and SQLAlchemy, and is suitable for internship-level projects.

Features ✨
- User Registration  
- User Login  
- Reset Password  
- Upload Document  
- Download Document  
- Edit Document  
- Delete Document  


Technologies Used 🛠️
Backend: Python, Flask, Flask-WTF, Flask-SQLAlchemy
Frontend: HTML, CSS
Database: SQLite
Others: Flask-Migrate for database migrations

Setup Instructions ⚡
Install Python 3.13+
Clone the repository:
git clone https://github.com/pragneshraval288-create/DMS-Project.git

Create virtual environment:
python -m venv venv

Activate virtual environment:
Windows: venv\Scripts\activate
Linux/Mac: source venv/bin/activate

Install required packages:
pip install -r requirements.txt

Apply database migrations:
flask db upgrade

Run the project:
flask run

Folder Structure 📂
backend/      # Flask backend code
Frontend/     # HTML templates & CSS files
Database/     # SQLite database file
instance/     # Flask instance folder

How to Use 🎯
Open http://127.0.0.1:5000/ in your browser
Register a user and log in
Upload and download documents

Demo / Screenshots 📸
![Register Page](backend/frontend/static/screenshots/register.png)
![Login Page](backend/frontend/static/screenshots/login.png)
![Reset Password](backend/frontend/static/screenshots/reset_password.png)
![Dashboard](backend/frontend/static/screenshots/dashboard.png)
![Upload Document](backend/frontend/static/screenshots/upload.png)
![View Document](backend/frontend/static/screenshots/view.png)

Notes 📝
This project is fully functional for internship purposes
Advanced features like search, role-based access, or file versioning can be added later for extra polish