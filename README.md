
# Hospital Management System

A **Flask-based web application** designed to simplify and manage hospital operations such as **patient registration, doctor management, appointment booking, and user authentication**. The system uses a database backend for storing hospital records and provides a clean web interface for interaction.

---

## 🚀 Features

* User authentication (signup/login)
* Manage patients and doctors
* Appointment booking system
* Editable patient/doctor details
* Database-driven design with `hms.sql`
* Responsive front-end with HTML/CSS and templates

---

## 📂 Project Structure

```
Hospital-Management-System-dbmsminiproject/
├── hospital system/
│   ├── hms.sql                # Database schema
│   ├── requirements.txt       # Python dependencies
│   ├── PROJECT/
│   │   ├── main.py            # Application entry point
│   │   ├── static/            # Static files (CSS, images)
│   │   ├── templates/         # HTML templates
│   │   │   ├── base.html
│   │   │   ├── index.html
│   │   │   ├── login.html
│   │   │   ├── signup.html
│   │   │   ├── booking.html
│   │   │   ├── doctor.html
│   │   │   ├── patient.html
│   │   │   └── ...
```

---

## 🛠️ Technologies Used

* **Python (Flask)** – Backend web framework
* **SQLite/MySQL** – Database (schema in `hms.sql`)
* **HTML, CSS** – Frontend templates
* **Bootstrap** (optional, if included in static files)

---

## ⚡ Getting Started

### Prerequisites

* Python 3.8+
* Virtual environment (recommended)
* Database (SQLite/MySQL)

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Hospital-Management-System.git
   cd Hospital-Management-System-dbmsminiproject/hospital system/PROJECT
   ```

2. Install dependencies:

   ```bash
   pip install -r ../requirements.txt
   ```

3. Import the database schema (`hms.sql`) into your database.

4. Run the application:

   ```bash
   python main.py
   ```

5. Open your browser at `http://127.0.0.1:5000/`

---



## 📖 Features in Detail

* **Login/Signup:** Secure user authentication
* **Patient Management:** Add, edit, and manage patient records
* **Doctor Management:** Add and view doctors
* **Appointments:** Book and manage appointments

---
