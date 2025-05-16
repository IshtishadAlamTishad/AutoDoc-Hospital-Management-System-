# 🏥 Automated Hospital Management System

## 📄 Description
C# application integrated with a database management system to streamline hospital workflows. The system offers:
- 🔐 Secure staff communication  
- 📑 Easy access to reports  
- 🛠️ Centralized admin oversight  

Designed for doctors, nurses, staff and administrators to collaborate efficiently and ensure better patient care.

---

## 🎬 Project Demonstration  
▶️ [Watch the demo video on YouTube](https://youtu.be/6YstV3XasoQ?si=dVq2R6ZP4FhCtX1X)

---

## ⚙️ Installation & How to Run 
  
  ### Prerequisites
    - .NET Framework (version 4.7.2 or later)
    - Microsoft SQL Server 
    - Visual Studio (for building and running the app)

  ### Setup Instructions
  - Clone or Download the Repository
  ```bash
    git clone <https://github.com/IshtishadAlamTishad/Automated-Hospital-Management-System->
    cd Automated-Hospital-Management-System
  ```
  ### Database Setup
    - Open Microsoft SQL Server Management Studio
    - Execute the provided SQL scripts to create the database schema and seed data
    - Update the connection string in app.config or web.config with your DB credentials
  
  ### Build and Run
    - Open the .sln solution file in Visual Studio
    - Restore NuGet packages if prompted
    - Build the solution
    - Run the application
  
  ### Login & Use
    - Login with appropriate credentials (Doctor, Nurse, Staff, Admin)
    - Navigate through your role-based features

---
## 🖼️ Screenshots

  ### Here are some features shown:
  ### 🔐 Login
  <p float="left">
    <img src="https://github.com/user-attachments/assets/a3708698-7381-4be6-8207-1cb5e0978658" width="45%" />
  </p>
  
  ### 📝 Signup
  <p float="left">
    <img src="https://github.com/user-attachments/assets/b8dfb99e-7a79-4a42-945e-7414a34d25e5" width="45%" />
  </p>
  
  ### 📋 Admin Features
  <p float="left">
    <img src="https://github.com/user-attachments/assets/b2caf876-c2af-4bec-9741-5a649de439fd" width="45%" />
    <img src="https://github.com/user-attachments/assets/82cbc25d-e4ff-4dc3-855a-9c792e9bc1c1" width="45%" />
  </p>
  
  <p float="left">
    <img src="https://github.com/user-attachments/assets/a897e615-0c1a-4315-bbde-2eceb5abc4f4" width="45%" />
    <img src="https://github.com/user-attachments/assets/57bee8fd-148d-4bd2-b937-f0159ee2a629" width="45%" />
  </p>
  
  <p float="left">
    <img src="https://github.com/user-attachments/assets/0294cc56-26c8-4165-a0e1-29ba81895030" width="45%" />
  </p>

  ### 🧑‍🤝‍🧑 Patient Features  
  <p float="left">
    <img src="https://github.com/user-attachments/assets/d1bad983-a6ff-4ee8-b095-27d499017dc5" width="32%" />
    <img src="https://github.com/user-attachments/assets/12722cd2-862b-41de-bc64-067c4c30cb69" width="32%" />
    <img src="https://github.com/user-attachments/assets/b262282b-601e-4736-972d-62571372dc4f" width="32%" />
  </p>

  
  ### 👨‍⚕️ Doctor Features
  <p float="left">
    <img src="https://github.com/user-attachments/assets/2ce1e4c7-63e5-4d70-b89b-4acd4dfe7c1a" width="32%" />
    <img src="https://github.com/user-attachments/assets/cf3a01f0-9659-43d9-9ea3-8125b09a4a7d" width="32%" />
    <img src="https://github.com/user-attachments/assets/41fad697-1998-4a67-93ae-779eef87b710" width="32%" />
  </p>
  
  ### 👩‍⚕️ Nurse Features
  <p float="left">
    <img src="https://github.com/user-attachments/assets/d603bccf-d6a2-4495-965b-370983bb82bd" width="32%" />
    <img src="https://github.com/user-attachments/assets/a5e3b03b-e3fa-4854-9f07-348fb51da832" width="32%" />
    <img src="https://github.com/user-attachments/assets/e95c0267-104b-421d-b126-1e89516f2360" width="32%" />
  </p>
  
  ### 🧑‍🔧 Staff Features
  <p float="left">
    <img src="https://github.com/user-attachments/assets/65c8d5c1-bbd4-4e01-b180-3c28a6a81b23" width="32%" />
    <img src="https://github.com/user-attachments/assets/715c5933-8b68-4811-b9eb-a27c3234b96c" width="32%" />
    <img src="https://github.com/user-attachments/assets/00996d6d-2846-42fb-b948-4312fe40a65e" width="32%" />
  </p>

---

## User Stories
    The system validates credentials and allows access upon correct input. Incorrect entries prompt error messages for wrong user ID or password.This hospital management system, developed using C#, supports an Admin and four other user roles: Doctor, Patient, Staff, and Nurse. The Admin has comprehensive control over user information, including the ability to add and remove users, manage inventory (medicines and health kits), view and delete patient report times, manage room availability, check patient reports, manage emergency rooms, and securely change passwords. Patients can securely log in, search for doctors, make appointments, purchase prescribed medicines, view report history, and communicate with other users via the chat panel. Doctors can manage appointments, write patient reports, manage medicine lists, and communicate through the chat panel. Staff can manage inventory, access patient schedules, and use the chat panel for communication. Nurses can check room availability, view duty schedules, manage patient medicines, and use the chat panel. The system prioritizes robust security measures and an intuitive interface, ensuring a user-friendly experience that empowers Admin and staff to efficiently manage information. New users must sign up before logging in.

  ### Structure
    Dashboard: Admin, Doctor, Patient, Staff, and Nurse can view their own details.
    
    Menu ->
    Manage Inventory:
    Admin, Staff: Medicines: View, Insert, Update, Delete Health Kits: View, Insert, Update, Delete
    
    Chat Panel:
    Admin: Communicate with patients, doctors, staff, and nurses. Doctor: Communicate with patients, staff, and admin. Patient: Communicate with admin, doctor, staff, nurse. Nurse: Communicate with admin, patient, doctor, staff.
    
    User Management:
    Admin: Manage user details (ID, name, password, Date of Birth, gender, type, picture, salary, balance) Insert, update, delete users Set initial balance and salary to zero on signup Search users by unique ID
    
    Appointments:
    Doctor: View appointment list with details. Patient: Make appointments and search for doctors. Staff: Access patient schedule for coordination.
    
    Schedule:
    Admin: View and delete patient report times and details. Nurse: View duty schedule.
    
    Control Rooms:
    Admin: Insert, update, delete rooms Search room types (e.g., ICU) Nurse: Check room availability and type.
    
    Medicine Management:
    Admin, Doctor, Staff, Nurse: View patient medicines list to ensure optimal patient care and safety.
    
    Reports:
    Doctor: Write and document patient information and treatment plans. Admin: Check patient reports and delete as needed.
    
    Miscellaneous (Admin):
    Check patient reports Manage emergency rooms Manage medicines Change password securely
    
    Buy Medicine:
    Patient: Purchase prescribed medicines.
    
    History:
    Patient: View report history.
    
    Terms & Conditions:
    Available on all user panels to ensure compliance with hospital management system rules.
---

## ✅ Conclusion
The Automated Hospital Management System brings together all stakeholders-patients, doctors, nurses, staff and administrators into one integrated platform.It simplifies operations,improves communication and enhances care delivery while enabling secure data access and efficient management workflows.

---

*Contributors :*

    Mohammed Istishad Alam Tishad (CSE,AIUB)
    Rimon Pramanik (CSE,AIUB)
    Tamzid Iqbal (CSE,AIUB)
    Md Faiyaz Mutadayin (CSE,AIUB)
