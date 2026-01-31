🩸 Blood Donation Management System

A web-based Blood Donation Management System developed using Flask and SQLite to efficiently manage blood donors, blood stock, hospital requests, and donation records. This project provides a simple and user-friendly interface for maintaining blood availability and supporting emergency blood requirements.

📌 Project Overview

The Blood Donation Management System is designed to digitize and streamline the process of blood donation and inventory management. It allows administrators to manage donor information, record blood donations, track blood stock by blood group, and handle hospital blood requests through a centralized platform.

🚀 Features

🧑‍⚕️ Donor Management

Register new donors

Update donor details

View donor donation history

🩸 Blood Donation Records

Record blood donations

Automatically update donor last donation date

🏦 Blood Bank Management

Add and manage blood banks

Associate donations with blood banks

📊 Blood Stock Management

Maintain total blood units available by blood type

Manual stock updates

View blood stock reports

🏥 Hospital Blood Requests

Submit blood requests

View and track requests

🔍 Eligible Donor Search

Search donors by blood group and city

🛠️ Technologies Used

Backend: Python, Flask

Database: SQLite (sqlite3 library)

Frontend: HTML, CSS

Templating Engine: Jinja2

Development Tool: VS Code

📂 Project Structure
Blood-Donation-Management-System/
│
├── .vscode/                     # VS Code configuration
│
├── static/                      # CSS files
│   ├── styledon.css
│   ├── stylemanage.css
│   ├── stylerecord.css
│   ├── styles.css
│   ├── stylesdonor.css
│   ├── stylesearch.css
│   ├── stylesprofile.css
│   ├── stylestock.css
│   ├── stylesubmit.css
│   └── styleview.css
│
├── templates/                   
│   ├── home.html
│   ├── manage_stock.html
│   ├── record_donation.html
│   ├── register_donor.html
│   ├── search_eligible_donors.html
│   ├── stock_report.html
│   ├── submit_blood.html
│   ├── update_profile.html
│   ├── view_donation_history.html
│   └── view_requests.html
│
├── venv/                        
│
├── app.py                      
├── bdms.db                      
├── create_db.py            
└── README.md                   

🧩 Database Tables

Donors

Hospitals

Blood_Banks

Donations

Blood_Requests

blood_stock

⚙️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/ajinajoseph/blood-donation-management-system.git
cd blood-donation-management-system

2️⃣ Install Dependencies
pip install flask

3️⃣ Initialize the Database
python database_setup.py

4️⃣ Run the Flask Application
python app.py

5️⃣ Open in Browser
http://127.0.0.1:5000/

👥 Team Information

Project Type: Group Project (4 Members)

Role: Backend integration, database design, frontend–backend connectivity

📌 Future Enhancements

User authentication for donors, hospitals, and blood banks

Role-based access control

Email/SMS notifications for urgent blood requests

Deployment on cloud platforms (Heroku / Render)

📄 License

This project is developed for academic purposes and learning.
Free to use and modify for educational use.
