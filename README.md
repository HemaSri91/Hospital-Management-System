# 🏥 Clinic/Hospital Management System

A user-friendly desktop application developed using **Python (Tkinter)** and **MySQL** to help clinics and hospitals manage patient records and appointments efficiently.


## 🚀 How to Run the Project

### ✅ Prerequisites
- Python 3.x
- MySQL Server
- Required Python Libraries:
  pip install pymysql Pillow
  
▶️ Steps to Launch
Step1-Open a terminal or Git Bash.
Step2-Navigate to the project folder.
Step3-Run the main Python file:
      python main.py
Step4-Login Credentials
      Username: abc
      Password: pqr

🛠️ Database Setup (MySQL)
Before running the app, set up the MySQL database:

CREATE DATABASE PATIENTS_DB;
USE PATIENTS_DB;

CREATE TABLE patients (
  MOBILE VARCHAR(200) PRIMARY KEY,
  NAME VARCHAR(200) NOT NULL,
  DOB VARCHAR(200) NOT NULL,
  HISTORY VARCHAR(200) NOT NULL,
  MEDICINES VARCHAR(200) NOT NULL
);

✨ Key Features
📁 Patient Record Management
-Add new patient details (Name, DOB, History, Medicines).
-Search patients by mobile number or name.
-View a complete list of all patients.
-Delete patient records when no longer needed.

📅 Appointment Management
Book appointments for patients.

Cancel or modify existing appointments.

View upcoming and past appointments.

🔐 Secure Login
Simple login screen to restrict access to authorized users.

🖼️ Project Screenshots
Login Page	Home Dashboard	Add Patient	View Patients	Delete Records
				

🧰 Tech Stack
Tool	 Usage
Python	 Core application logic
Tkinter	 GUI framework
MySQL	 Backend database
PyMySQL	 Python-MySQL connector
Pillow	 Image handling (for GUI icons/images)

📌 Folder Structure
Clinic-Hospital-Management-System/
│
├── main.py             
├── Login_PAGE.py           
├── page_after_login.py   
├── AddPatients.py        
├── view_patients.py       
├── ...                      

📚 About the Project
This Clinic/Hospital Management System is developed to:
1.Minimize manual patient record keeping
2.Simplify appointment tracking
3.Provide easy search and retrieval of patient information
4.Ensure basic access control through login
5.It is ideal for small clinics and medical centers looking for a lightweight and easy-to-use management tool.

🤝 Support
For any queries or issues, feel free to raise an issue or contact the developer.
