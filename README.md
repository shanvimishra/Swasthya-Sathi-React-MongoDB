# 🏥 Swasthya Sathi – Smart Healthcare Management System

_A secure, role-based digital healthcare platform to manage patients, doctors, and hospital operations efficiently._

---

## 📌 Table of Contents
- [Overview](#overview)
- [Business Problem](#business-problem)
- [System Modules](#system-modules)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Core Functionalities](#core-functionalities)
- [Security & Authentication](#security--authentication)
- [Future Scope](#future-scope)
- [How to Run This Project](#how-to-run-this-project)
- [Final Impact](#final-impact)
- [Author & Contact](#author--contact)

---

## Overview

**Swasthya Sathi** is a smart healthcare management system that digitizes hospital workflows and improves patient care by providing a centralized, secure, and role-based platform for hospitals, clinics, and diagnostic centers.

---

## Business Problem

Traditional healthcare systems face major challenges such as:

- Manual patient records and paper files  
- Appointment scheduling delays  
- Loss of medical history  
- Poor doctor–patient coordination  
- Data security risks  

**Swasthya Sathi** solves these problems with a modern digital healthcare platform.

---

## System Modules

### 👩‍⚕️ Patient Module
- Register & Login  
- Book appointments  
- View medical history  
- Download prescriptions  
- Notifications  

### 🧑‍⚕️ Doctor Module
- View assigned appointments  
- Access patient history  
- Upload prescriptions & reports  
- Add diagnosis  

### 🏥 Admin Module
- Manage users  
- Approve doctors  
- Monitor system activity  
- View analytics  

---

## Tech Stack

| Layer | Technology |
|------|------------|
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Backend | Python (Flask) / Java (Spring Boot) |
| Database | MySQL |
| Authentication | JWT / Sessions |
| Hosting | AWS / Render |

---

## Project Structure

swasthya-sathi/
│
├── README.md
├── .gitignore
├── requirements.txt
│
├── frontend/
│ ├── index.html
│ ├── login.html
│ ├── dashboard.html
│
├── backend/
│ ├── app.py
│ ├── models/
│ ├── routes/
│ └── services/
│
├── database/
│ └── swasthya.sql
│
├── docs/
│ └── Swasthya_Sathi_Report.pdf




---

## Core Functionalities

- Online appointment booking  
- Digital medical records  
- Prescription management  
- Doctor–patient communication  
- Admin control panel  
- Automated alerts  

---

## Security & Authentication

- Password hashing  
- Role-based access  
- Secure APIs  
- JWT / session authentication  
- SQL injection protection  

---

## Future Scope

- AI symptom checker  
- Video consultations  
- Mobile application  
- Cloud storage  
- Online payments  

---

## How to Run This Project

1. Clone repository  
```bash
git clone https://github.com/shanvimishra/Swasthya-Sathi-React-MongoDB.git
cd swasthya-sathi

pip install -r requirements.txt
python backend/app.py


Setup database

Create database: swasthya_sathi

Import database/swasthya.sql

Run frontend
Open frontend/index.html in browser



