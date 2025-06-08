# Online Examination System
The Online Examination System is a web-based platform designed to simplify and automate the process of conducting exams digitally. It allows administrators to create, manage, and schedule exams, while candidates can log in securely, attempt tests, and receive instant results.

🔧 Features
🧑‍🏫 Admin panel for managing users and exams

📝 Support for multiple question types (MCQs, True/False, Short Answer)

⏲️ Timed examinations with countdown

🔐 Secure login and role-based access (Admin, Examiner, Student)

📊 Auto-evaluation and instant result generation

📁 Question bank with randomization


💻 Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: Java, Servlet, Jsp

Database: MySQL 

# 📂 Folder Structure
online-examination-system/
│
├── 📁 assets/                  # Static assets (images, fonts, icons)
│   ├── images/
│   └── icons/
│
├── 📁 css/                     # Stylesheets
│   └── style.css
│
├── 📁 js/                      # JavaScript files
│   └── main.js
│
├── 📁 pages/                   # HTML Pages
│   ├── index.html             # Home/Login Page
│   ├── dashboard.html         # Student/Teacher Dashboard
│   ├── exam.html              # Exam interface
│   └── result.html            # Show results
│
├── 📁 backend/                 # Backend logic
│   ├── database/              # DB connection and queries
│   │   └── db.js / db.java / db.php
│   ├── controllers/           # Business logic
│   │   ├── examController.js
│   │   └── authController.js
│   └── routes/                # API routes
│       └── apiRoutes.js
│
├── 📁 uploads/                # For uploading questions/images
│
├── 📁 config/                 # Configuration files
│   └── config.js / dbconfig.php
│
├── 📁 models/                 # Data Models (for DB structure)
│   └── userModel.js / examModel.js
│
├── 📁 services/               # Helper functions (authentication, mail etc.)
│
├── 📁 test/                   # Unit or integration tests
│
├── 📄 package.json / pom.xml  # Project metadata (depends on tech used)
├── 📄 README.md               # Project description
└── 📄 index.js / server.js    # Main server entry point

🛠️ Installation & Setup Instructions
Follow the steps below to set up and run the Online Examination System on your local machine:

🔧 Prerequisites
Make sure you have the following installed:

🖥️ For Java-based Project (using Servlets/JSP):
Java JDK 8 or later

Apache Tomcat (v9+)

MySQL Server

MySQL Workbench (optional)

Apache NetBeans or IntelliJ IDEA

📦 Step-by-Step Setup
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Devesh1999-dev/online-examination-system.git
cd online-examination-system
2. Set Up the Database
Open MySQL Workbench.

Create a new database:

sql
Copy
Edit
CREATE DATABASE online_exam;
Import the provided SQL file (if included) or manually create tables:

sql
Copy
Edit
USE online_exam;
-- CREATE TABLE users, questions, results, etc.
3. Configure the Project in IDE
Open the project in NetBeans/IntelliJ.

Configure your Tomcat server in the IDE.

Link the project to the server runtime.

4. Set Database Credentials
Go to the backend DB config file:

bash
Copy
Edit
/backend/database/db.java  (or config/db.php / db.js)
Update it with your local MySQL credentials:

java
Copy
Edit
String url = "jdbc:mysql://localhost:3306/online_exam";
String user = "root";
String password = "your_password";
5. Run the Project
Deploy the project to Tomcat.

Start the server.

Access it via your browser:

bash
Copy
Edit
http://localhost:8080/online-examination-system/
✅ Optional Features to Set Up
Admin Login (to add questions, view results)

Student Login (to take exam)

Timer during exam

MCQ-based quiz

Result auto-calculation and display

# after successfull installtion of the libraries, run FRAS-GUI-Version.py

# How to use the app (User Guide)
1. click on add student button from the left sidebar
   ![Screenshot 2024-12-14 152431](https://github.com/user-attachments/assets/98b01364-0869-4de1-adf6-660e66ccc1c8)










