Flask Project 1 — Beginner Backend Learning Project

This project is part of my journey into backend development using Python and Flask.
It includes basic routing, templates, and Jinja2 logic as I learn how real web applications are structured.

Features

Flask application structure (app, routes, templates)

Dynamic pages rendered with Jinja2

Base template with HTML inheritance

Error / success alert messages using flash()

Auto-reload enabled with debug mode

Clean project folder organization

📂 Project Structure
Flask project/
│
├── website/
│   ├── __init__.py
│   ├── views.py
│   ├── models.py
│   └── templates/
│       ├── base.html
│       └── home.html
│
├── main.py
└── README.md

🛠 How to Run This Project
Create & activate a virtual environment
python -m venv venv


Activate:

Windows

venv\Scripts\activate

Install dependencies
pip install flask


If you have a requirements.txt, then:

pip install -r requirements.txt

Run the project
python main.py


Your app will start at:

 http://127.0.0.1:5000

 Future Improvements

Add user authentication (login/signup)

Connect to a database (SQLite or MySQL)

Add form validation

Deploy to Render or Railway

Author

Oyinade Olayinka
Learning backend development with Python & Flask 
