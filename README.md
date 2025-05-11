# Clinic-Booking-System
A MySQL-based database management system for clinic appointments and treatment tracking.


# Clinic Booking System

## Description
A database management system for scheduling clinic appointments, storing patient records, and tracking treatments.

## Setup Instructions
1. Install MySQL on your local machine.
2. Clone the repository:

3. Navigate to the SQL folder and import the database:
```sql
mysql -u your_user -p your_password < clinic_booking.sql



---

🚀 **Final Steps**
- 📌 Push your repository to GitHub  
- 🖼 Upload your ERD image  
- ✅ Review and test your database schema  


# Clinic Booking System

## 📌 Description
The **Clinic Booking System** is a relational database designed using **MySQL** to manage clinic appointments, patient records, doctor schedules, and treatment tracking. It ensures efficient and structured data storage with proper relationships between patients, doctors, appointments, and treatments.

## 🛠 Features
- **Manage patient records** with basic details.
- **Schedule doctor appointments** with date and time.
- **Track treatments** administered to patients.
- **Define doctor specialties** for better booking.
- **Establish relationships** between patients, doctors, and treatments.

## 🗄 Database Schema (ERD)
The database consists of five main entities:
- **Patients** (`PatientID`, `Name`, `DOB`, `Gender`, `ContactInfo`)
- **Doctors** (`DoctorID`, `Name`, `Specialty`, `ContactInfo`)
- **Appointments** (`AppointmentID`, `PatientID`, `DoctorID`, `Date`, `Time`)
- **Treatments** (`TreatmentID`, `Name`, `Description`)
- **Patient_Treatments** (`PatientID`, `TreatmentID`) → M:N between Patients & Treatments

### 📌 ERD Diagram
![Clinic ERD](./ERD/clinic_erd.png)

## 🏗 Project Structure
