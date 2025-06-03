# todo
📝 Todo App - Django
This is a simple Todo List Web Application built with Django. Users can sign up, log in, add tasks, edit them, and delete them. Each user's tasks are stored separately.

🚀 Features
User Signup & Login (with authentication)

Add Tasks

Edit Tasks

Delete Tasks

Logout

Each user can see only their own tasks



🛠️ Tech Stack
Backend: Django (Python)

Frontend: HTML, CSS (Inline styling)

Database: SQLite (default Django database)

⚙️ How to Run the Project
Clone the Repository

bash
Copy
Edit
git clone https://github.com/IqraFatimaaa/django-todo-app.git
cd django-todo-app

Create and Activate a Virtual Environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate     # For Linux/macOS
venv\Scripts\activate        # For Windows
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Apply Migrations

bash
Copy
Edit
python manage.py makemigrations
python manage.py migrate
Run the Server

bash
Copy
Edit
python manage.py runserver
Open the App

Go to http://127.0.0.1:8000/signup in your browser to register.

Then log in and start adding your tasks.

📁 Project Structure
pgsql
Copy
Edit
todoapp/
│
├── templates/
│   ├── signup.html
│   ├── login.html
│   ├── todo.html
│   └── delete_todo.html
│
├── todoapp/
│   ├── views.py
│   ├── urls.py
│   └── models.py
│
├── manage.py
└── README.md
 Author
Your Name Iqra Nadeem
 License
This project is open-source and free to use.

