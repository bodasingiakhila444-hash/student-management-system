📚 Student Management System

A web-based Student Management System developed using Flask (Python) that allows users to manage student records efficiently. The system supports student registration, login authentication, viewing records, editing details, and deleting data.

🚀 Features

🔐 User Login & Authentication

📝 Student Registration

📋 View Student Records

✏️ Edit Student Details

❌ Delete Student Records

🎨 Responsive UI using CSS

🗂 Organized Project Structure (Templates & Static folders)

🛠 Technologies Used

🐍 Python

🌶 Flask

🌐 HTML5

🎨 CSS3

🗄 SQLite (or your database if used)

📂 Project Structure
Student-Management-System/
│
├── app.py
├── README.md
├── env/
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── view.html
│   ├── edit.html
│
└── static/
    └── style.css
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/student-management-system.git
cd student-management-system
2️⃣ Create Virtual Environment (If not created)
python -m venv env
3️⃣ Activate Virtual Environment

Windows:

env\Scripts\activate

Mac/Linux:

source env/bin/activate
4️⃣ Install Required Packages
pip install flask

(If requirements.txt exists, use: pip install -r requirements.txt)

▶️ Run the Application
python app.py

Open your browser and go to:

http://127.0.0.1:5000/
📌 Description of Files
🔹 app.py

Contains backend logic including:

Routing

Database operations

Form handling

CRUD operations

🔹 templates/

Contains all HTML pages:

index.html → Home page

login.html → User login

register.html → Student registration

view.html → View all students

edit.html → Edit student details

🔹 static/style.css

Contains styling for UI design.

🔹 env/

Virtual environment folder (contains installed dependencies).

🔮 Future Improvements

Add search functionality

Add pagination

Password encryption

Role-based access (Admin/User)

Export data to PDF/Excel

Deploy on cloud (Heroku / Render)

👩‍💻 Author

Developed by Bodasingi Akhila

📜 License

This project is for educational purposes.
