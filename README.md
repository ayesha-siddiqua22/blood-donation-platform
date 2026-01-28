# blood-donation-platform
## 📁 Project Structure

```
blood-donation-platform/
│
├── backend/                 # Django backend
│   ├── manage.py
│   └── blood_app/
│
├── frontend/                # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
│
├── README.md
├── LICENSE
└── .gitignore
```

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
