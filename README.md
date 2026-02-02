🌍 Disaster Management System (Flask + MySQL)

A web-based Disaster Management System built using Flask and MySQL to manage and track disasters, affected victims, relief camps, volunteers, rescue teams, resources, donors, and donations.

This project provides full CRUD functionality with proper form validation and a relational database design, making it suitable for academic projects, DBMS coursework, and backend portfolio demonstrations.

🚀 Features

Manage Locations (City, District, State)

Track Disasters with date, time, type, and location

Maintain Relief Camps and their capacities

Register and manage Victims

Manage Volunteers and Rescue Teams

Track Resources and availability

Handle Donors and Donations

Dashboard with:

Total counts of entities

Total donation amount

Secure form handling using Flask-WTF

MySQL database integration using mysql-connector-python

🛠 Tech Stack

Backend: Flask (Python)

Database: MySQL

Forms & Validation: Flask-WTF, WTForms

Frontend: HTML, CSS (Jinja2 templates)

Version Control: Git & GitHub

📂 Project Structure
disaster_prep/
├── app.py
├── config_example.py
├── requirements.txt
├── templates/
├── static/
└── database.txt

⚙️ Setup Instructions (Run Locally)
1️⃣ Clone the repository
git clone https://github.com/your-username/disaster-prep-flask.git
cd disaster-prep-flask

2️⃣ Create a virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Configure database

Create a MySQL database

Create tables using database.txt

Create a file named config.py in the project root:

class Config:
    MYSQL_HOST = "localhost"
    MYSQL_USER = "root"
    MYSQL_PASSWORD = "your_password"
    MYSQL_DB = "your_database"
    SECRET_KEY = "your_secret_key"


⚠️ Do NOT upload config.py to GitHub
Use config_example.py as a reference.

5️⃣ Run the application
python app.py


Open in browser:

http://127.0.0.1:5000/

🔐 Security Notes

Sensitive credentials are excluded using .gitignore

config_example.py is provided for reference

Actual credentials remain local

📌 Future Improvements

Authentication and role-based access

Dropdowns instead of manual ID entry

REST API support

Analytics dashboard

Cloud deployment

🎓 Academic Use

This project is suitable for:

DBMS Mini Project

Flask Backend Demonstration

Resume / Internship Portfolio

College Submissions

📜 License

This project is for educational purposes.