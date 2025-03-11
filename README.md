# SmartAttendQR-Smart-Attendance-with-QR-

Student Attendance System using QR Code

A Django-based web application for managing student attendance using QR codes. This system allows faculty members to efficiently record attendance by scanning QR codes generated for students. The project ensures accuracy and eliminates manual attendance tracking.

📌 Features

✅ QR Code Generation: Unique QR codes for each student

✅ QR Code Scanning: Faculty can scan student QR codes to mark attendance

✅ Automated Attendance Records: Attendance is logged in the database instantly

✅ Student & Faculty Management: Secure login for both students and faculty

✅ Database Storage: Uses SQLite (can be upgraded to MySQL/PostgreSQL)

✅ User Authentication: Role-based access control for students and faculty

✅ Attendance Reports: View and export attendance records

✅ Responsive UI: Web-based interface accessible from any device




🛠️ Installation & Setup



Prerequisites



Ensure you have the following installed:

Python 3.x

Django

pip (Python package manager)

Virtual environment (recommended)




Steps to Set Up

Clone the repository

git clone https://github.com/yourusername/StudentAttendanceQR.git
cd StudentAttendanceQR

Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies

pip install -r requirements.txt

Run migrations

python manage.py migrate

Create a superuser (for admin access)

python manage.py createsuperuser

Follow the prompts to set up an admin username and password.

Start the development server

python manage.py runserver

Access the application
Open your browser and go to:

http://127.0.0.1:8000/ (Home Page)

http://127.0.0.1:8000/admin/ (Admin Panel)




📂 Project Structure

StudentAttendanceQR/
│-- FacultyView/
│   │-- migrations/
│   │-- static/
│   │-- templates/
│   │-- __init__.py
│   │-- admin.py
│   │-- apps.py
│   │-- models.py
│   │-- urls.py
│   │-- views.py
│-- StudentAttendanceQR/
│-- db.sqlite3
│-- manage.py
│-- requirements.txt
│-- README.md

FacultyView/ - Django app for faculty interactions

models.py - Defines database schema for students, faculty, and attendance records

views.py - Handles user requests and attendance logic

urls.py - Defines application routes

templates/ - Contains frontend HTML templates

db.sqlite3 - SQLite database (can be replaced with MySQL/PostgreSQL)

manage.py - Django management script

requirements.txt - List of dependencies




📸 How It Works

Faculty logs in and generates QR codes for students.

Students scan their QR codes using the web application.

Attendance is recorded automatically in the database.

Faculty can view attendance reports and export records if needed.



🚀 Future Enhancements

🔹 Mobile App Integration (Android/iOS for scanning)

🔹 Real-time Notifications (Email/SMS alerts for students)

🔹 Face Recognition (Alternative method for attendance tracking)

🔹 Cloud Database Support (AWS, Firebase, or PostgreSQL)

🔹 Detailed Analytics & Insights



🏷️ License

This project is licensed under the MIT License.



📧 Contact

For any inquiries or suggestions, feel free to reach out:



GitHub: mukeemansari69

Email: mukeemansari038@gmail.com
