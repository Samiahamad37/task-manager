Task Manager System – Django

A simple, clean, and efficient Task Manager System built using Django, designed to help users manage tasks, track progress, and stay organized.
The system supports creating tasks, updating them, marking them as completed, and deleting them, with a secure authentication flow.

📌 Features
 User Features

User registration & login

Password-hashed authentication

Add new tasks

Edit/update tasks

Mark tasks as completed or pending

Delete tasks

View dashboard of all tasks

Responsive UI (Bootstrap)

⚙️ System Features

Django MVC architecture

CRUD operations for tasks

Django Admin Panel

CSRF protection

PostgresSQL database

Clean, simple folder structure

🚀 Technologies Used
Component	Technology
Frontend	HTML, CSS, Bootstrap
Backend	Django (Python)
Database	PostgreSQL
Tools	Git, GitHub

🔧 Installation & Setup
1. Clone the repository
git clone https://github.com/Samiahamad37/task-manager.git
cd task-manager

2. Create a virtual environment
python -m venv env

3. Activate the environment

Windows:

venv\Scripts\activate


Linux/Mac:

source venv/bin/activate

4. Install dependencies
pip install -r requirements.txt

5. Apply migrations
python manage.py migrate

6. Run the server
python manage.py runserver


Now open 👉 http://127.0.0.1:8000/

🧪 How to Use

Register an account

Log in

Create a new task from the dashboard

Edit, complete, or delete tasks

Log out when done


🛠️ Future Improvements

Add user roles

Add deadlines & reminders

Add task categories

Add priority levels

Add REST API (DRF)

Add charts for analytics

🤝 Contributing

Pull requests are welcome!
If you’d like to propose a feature, open an issue first.
