# BlueCred 🌱

A transparent environmental compliance platform that records industrial pollution data, verifies audits, and maintains trusted records using an append-only audit database system.

## 🚀 Live Demo

https://bluecred-deployed.onrender.com

---

## 📌 About The Project

BlueCred is a web-based environmental monitoring platform designed to improve trust and transparency between industries, auditors, and the public.

The platform allows industries to maintain pollution records, auditors to verify compliance reports, and users to view publicly available industry information.

The system uses a cryptographically secured append-only audit record mechanism to preserve historical integrity.

---

<img width="1629" height="682" alt="Screenshot From 2026-06-17 00-18-33" src="https://github.com/user-attachments/assets/42581c74-addf-4a4e-91b8-fa51e659a0a6" />


## ✨ Features

### Public Registry
- View registered industries
- Search industries by name or ID
- Filter by category and compliance score
- View audit reports

### Auditor Dashboard
- Secure auditor login
- Create and manage audit reports
- Track industry compliance data

### Data Integrity
- Append-only audit records
- Cryptographic hashing of records

### Backend
- REST APIs using Flask
- PostgreSQL database
- SQLAlchemy ORM
- Production deployment using Gunicorn

---

## 🛠️ Tech Stack

### Backend
- Python
- Flask
- Flask-SQLAlchemy
- PostgreSQL
- Gunicorn

### Frontend
- HTML5
- CSS3
- JavaScript
- Jinja Templates

### Deployment
- Render Cloud
- GitHub

---

## 📂 Project Structure


bluecred_progress/

│
├── app/
│ ├── routes/
│ ├── models/
│ ├── templates/
│ ├── static/
│ └── init.py
│
├── run.py
├── requirements.txt
├── Procfile
└── README.md


---

## ⚙️ Local Setup

Clone repository:

```bash
git clone https://github.com/devkaransingh1/Bluecredprogress.git

Enter directory:

cd Bluecredprogress

Create virtual environment:

python -m venv .venv

Activate:

Linux:

source .venv/bin/activate

Install dependencies:

pip install -r requirements.txt

Create environment variables:

DATABASE_URL=your_postgresql_url
SECRET_KEY=your_secret_key

Run application:

python run.py
🔐 Security

BlueCred uses:

Environment-based secret configuration
Database access control
Append-only audit storage
Hash-based record verification
📊 Database

Main database:

PostgreSQL

Important tables:

Industries
Auditors
Audit Reports

Audit reports are designed to preserve historical records by preventing modification of previous entries.

👨‍💻 Author

Dev Karan Singh (Backend, Frontend and Database(postgresql))

Computer Science (AI) Student

GitHub:
https://github.com/devkaransingh1
