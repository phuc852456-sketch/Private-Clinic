# Private Clinic Management System

This project is a **Clinic / Hospital Management System** developed using **ASP.NET MVC (C#)**.
The system helps manage doctors, patients, appointments, and schedules in a private clinic environment.

It demonstrates a typical **healthcare management web application** with multiple user roles and administrative features.

---

# Features

## Doctor Management

* Add, edit, and delete doctors
* Manage doctor information
* View doctor schedules

## Patient Management

* Register new patients
* Update patient information
* View patient records

## Appointment Management

* Book appointments
* Manage appointment schedules
* Track appointment status

## Admin Management

* Manage users and roles
* Monitor system operations
* Manage clinic data

## Schedule Management

* Create doctor schedules
* Assign available time slots
* Manage working hours

---

# System Architecture

The project follows the **ASP.NET MVC architecture pattern**.

Project layers include:

Controllers
Models
Views
Services
Data
Helpers
Filters
Migrations
Scripts

---

# Technologies Used

ASP.NET MVC
C#
Entity Framework
SQL Server
Razor View Engine
Bootstrap
JavaScript / jQuery

---

# Project Structure

```
Private-Clinic
│
├── Controllers
├── Models
├── Views
├── Services
├── Data
├── Scripts
├── Content
├── Migrations
│
├── HospitalDB.sln
├── HospitalDB.csproj
├── Web.config
├── script.sql
└── README.md
```

---

# Database Setup

The system uses **SQL Server** as the database.

To create the database:

1. Open SQL Server Management Studio
2. Run the file:

```
script.sql
```

Optional sample data:

```
Sample_Data.sql
```

---

# How to Run the Project

1. Clone the repository

```
git clone https://github.com/your-username/private-clinic.git
```

2. Open the solution file:

```
HospitalDB.sln
```

3. Restore NuGet packages

4. Create the database by running:

```
script.sql
```

5. Run the project using Visual Studio

---

# System Roles

The system includes multiple user roles:

Admin
Doctor
Patient
Receptionist

Each role has different permissions within the system.

---

# Future Improvements

Add online appointment booking
Add email notifications
Improve user interface
Add REST API support

---

# Author

This project was developed as a practice project for learning **ASP.NET MVC and full-stack web development**.
