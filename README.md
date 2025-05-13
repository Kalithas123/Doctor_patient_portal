A full-stack Java web application that facilitates seamless interaction between doctors and patients. The system enables appointment scheduling, prescription management, and administrative oversight, aiming to digitize and streamline healthcare services.

📌 Table of Contents
Features

Technologies Used

Installation

Usage

Screenshots

Contributing

License

✅ Features
User Roles:

Admin: Manage doctors, patients, and appointments.

Doctor: View appointments, manage patient records, and provide prescriptions.

Patient: Book appointments, view prescriptions, and manage personal information.

Functionalities:

Secure authentication for all user roles.

Appointment scheduling with conflict checks.

Prescription management with history tracking.

Responsive design for accessibility on various devices.

🛠 Technologies Used
Frontend:

HTML5, CSS3, Bootstrap 5

JavaScript

Backend:

Java Servlets, JSP, JSTL

JDBC for database connectivity

Database:

MySQL

Tools & Platforms:

Apache Tomcat

Eclipse IDE

Git for version control

🚀 Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/yourusername/doctor-patient-management.git
Import Project:

Open Eclipse IDE.

Import as an existing Maven project.

Database Setup:

Create a MySQL database named hospital_db.

Import the hospital_db.sql file located in the database directory.

Configure Database Connection:

Update the DBConnection.java file with your MySQL credentials.

Deploy Application:

Add the project to your Apache Tomcat server.

Start the server and access the application at http://localhost:8080/doctor-patient-management/.

💻 Usage
Admin:

Login with admin credentials.

Navigate to the dashboard to manage doctors, patients, and appointments.

Doctor:

Login with assigned credentials.

View scheduled appointments and manage patient records.

Patient:

Register for a new account.

Login to book appointments and view prescriptions.

