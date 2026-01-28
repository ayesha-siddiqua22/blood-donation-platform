# 🩸 Blood Donation Platform

A full-stack **Blood Donation Platform** developed using **Django (Backend)** and **React (Frontend)** to connect blood donors, recipients, hospitals, and blood banks in real time. The goal is to make blood availability faster, transparent, and reliable during emergencies.

---

## 📌 Brief About the Idea

The Blood Donation Platform is a digital solution designed to simplify and speed up the process of finding blood donors. It provides a centralized system where donors can register, patients can request blood, and hospitals can manage blood availability efficiently.

---

## ❗ Problem Statement

In emergency situations, patients often face delays in finding suitable blood donors due to lack of real-time information, poor communication, and absence of a centralized platform.

---

## 💡 Proposed Solution

This platform bridges the gap between donors and recipients by providing real-time access to donor information, blood requests, and hospital coordination through a web-based application.

---

## 🎯 Customers / Target Audience / Beneficiaries

The platform is useful for blood donors, patients in need of blood, hospitals, blood banks, NGOs, and healthcare organizations involved in blood donation activities.

---

## 🚀 Present State of the Idea / Activities Done

The project is currently under development. Core planning, system design, frontend structure, and backend setup using Django and React have been completed, and further feature implementation is ongoing.

---

## ⏭️ Next Steps

Future improvements include secure authentication, location-based donor matching, notification services, improved UI/UX, and deployment on a cloud platform.

---

## ✨ Key Features

### Backend (Django)
- Donor registration and management  
- Blood request handling  
- REST APIs using Django REST Framework  
- Admin panel for hospital/admin control  

### Frontend (React)
- User-friendly interface for donors and recipients  
- Forms for donor registration and blood requests  
- Display of available donors and blood groups  
- Responsive design for desktop and mobile  

---

## 🛠️ Technology Stack

### Frontend
- React  
- JavaScript  
- HTML  
- CSS  

### Backend
- Python  
- Django  
- Django REST Framework  

### Database
- SQLite (can be extended to MySQL/PostgreSQL)

---

## ⚙️ Installation & Execution

### Backend Setup (Django)

```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install django djangorestframework
cd backend
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Backend runs at:  
http://localhost:8000

---

### Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```

Frontend runs at:  
http://localhost:3000
