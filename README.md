Flask User Management App (SQLite)

A simple Flask web application that allows users to submit their name and email through a form and stores the data in an SQLite database. The submitted records are displayed dynamically on the homepage.

🚀 Features

Add user details (Name & Email) via HTML form

Store data persistently using SQLite

Display all stored users on the homepage

Uses Flask routing, templates, and redirects

Lightweight and beginner-friendly project

🛠 Tech Stack

Python

Flask

SQLite

HTML (Jinja2 templates)

📂 Project Structure
project/
│
├── app.py
├── database.db
└── templates/
    └── index.html

⚙️ How It Works

User enters name and email in the form.

On form submission (POST request):

Data is inserted into the SQLite database.

User is redirected back to the homepage.

On page load (GET request):

All stored users are fetched from the database.

Data is rendered dynamically using index.html.

▶️ How to Run the Project

Clone the repository

git clone <repo-url>
cd project


Install Flask

pip install flask


Create SQLite Database

CREATE TABLE users (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    name TEXT NOT NULL,
    email TEXT NOT NULL
);


Run the application

python app.py


Open browser and visit:

http://127.0.0.1:5000/

📌 Future Enhancements

Input validation

Delete / Update user records

Flash messages for success/error

Authentication system

Deployment on cloud platform

👩‍💻 Author

Shubhada Wani
Python | Flask | Full Stack Enthusiast
