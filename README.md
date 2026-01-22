📝 To-Do List Web Application (Flask)
📌 Project Overview

The To-Do List Web Application is a simple and user-friendly task management system built using Python Flask and SQLite. It allows users to add, view, update, and manage daily tasks efficiently through a web interface.

This project demonstrates backend development using Flask, database handling with SQLite, and template rendering using Jinja2.

🎯 Features

➕ Add new tasks

📋 View all tasks

🔄 Update task status (Pending / Completed)

🗑️ Delete tasks

💾 Persistent storage using SQLite database

🌐 Web-based interface using HTML templates

🗂️ Project Structure
todo-list-app/
│
├── app.py                # Main Flask application
├── todo.db               # SQLite database
├── templates/            # HTML templates
│   └── *.html
└── README.md

🛠️ Technologies Used

Python 3

Flask

SQLite

HTML (Jinja2 Templates)

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/todo-list-app.git

2️⃣ Navigate to Project Directory
cd todo-list-app

3️⃣ Create & Activate Virtual Environment (Optional but Recommended)
python -m venv venv
venv\Scripts\activate

4️⃣ Install Dependencies
pip install flask

5️⃣ Run the Application
python app.py

🌍 Access the Application

Open your browser and go to:

http://127.0.0.1:5000/

⚠️ Notes

This application uses Flask’s development server.

Do not use this setup for production environments.

Database (todo.db) is created automatically on first run.

🔮 Future Enhancements

User authentication (login & register)

Task priorities and deadlines

Search and filter tasks

Responsive UI with CSS framework

REST API support

<img width="1920" height="1080" alt="Screenshot 2026-01-22 141853" src="https://github.com/user-attachments/assets/d4b5d32d-bdfa-4cf2-825e-95b3b2717daf" />

<img width="1920" height="1080" alt="Screenshot 2026-01-22 141808" src="https://github.com/user-attachments/assets/cbdc8800-194d-414a-a03b-1951159a47d9" />
