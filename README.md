# Doit
A task management web application.

## Description:
Doit is a web-based task management application that allows users to create, track, and complete their daily tasks efficiently.

## Built with
- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
- ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
- ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS](https://img.shields.io/badge/css-%23663399.svg?style=for-the-badge&logo=css&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
- ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
- ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

## Features
* **Smart Authentication:** Supports login via both **username and email**, with automatic redirection for unauthenticated users.
* **Task Dashboard:** Interactive table displaying active tasks with due dates and quick "mark as complete" actions.
* **History Log:** Dedicated view for completed tasks, allowing users to track their productivity history.
* **Secure Profile Management:** Users can update sensitive info (email, username), protected by a **password verification** step before saving changes.
* **Responsive Forms:** Clean interfaces for task creation and registration using generic date pickers and validation.

## File Structure
├── static/          # CSS, JavaScript, Assets

├── templates/       # HTML Templates (Jinja2)

├── app.py           # Application entry point & Routes

├── app.db           # SQLite Database

└── requirements.txt # Project dependencies

## How to Run
> The following commands assume a Unix-like environment (Bash).

1. Make sure you have Python 3 installed.

2. Clone this repository and navigate to the project directory.

3. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
5. Run the development server:
   ```bash
   flask run
   ```
   
6. Open your browser and go to:
   ```
   http://127.0.0.1:5000
   ```
