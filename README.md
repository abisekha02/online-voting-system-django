# Online Voting System

A secure web-based **Online Voting System** developed using **Django** that enables digital elections through a centralized platform. The application provides role-based access for administrators and voters, allowing secure voter registration, candidate management, vote casting, and real-time election result generation.

---

## Overview

The Online Voting System digitizes the traditional voting process by providing a secure, transparent, and user-friendly platform for conducting elections. The system ensures that each registered voter can vote only once while administrators manage elections, candidates, and voting results.

---

## Features

### Administrator Module

- Admin Login
- Dashboard
- Add/Edit/Delete Candidates
- Manage Elections
- Manage Voters
- View Election Results
- Monitor Voting Statistics
- Generate Reports

---

### Voter Module

- Secure Login
- Voter Registration
- View Candidate List
- Cast Vote
- One Vote Per User
- View Election Status
- Profile Management

---

## Election Management

- Candidate Registration
- Election Creation
- Voting Start & End Dates
- Vote Counting
- Winner Declaration
- Live Result Calculation

---

## Security Features

- Django Authentication
- Role-Based Access Control
- Secure Login
- One Vote Per Registered User
- CSRF Protection
- Session Management
- Database Validation

---

## Tech Stack

### Backend

- Django
- Python

### Frontend

- HTML5
- CSS3
- Bootstrap
- JavaScript

### Database

- SQLite (Development)
- MySQL/PostgreSQL (Production)

---

## Project Structure

```text
Online-Voting-System/
│
├── votinghome/
├── votingproject/
├── votingcontact/
├── votingresult/
├── votingwebsite/
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/online-voting-system-django.git
```

Navigate to the project

```bash
cd online-voting-system-django
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run database migrations

```bash
python manage.py migrate
```

Start the development server

```bash
python manage.py runserver
```

Open your browser

```
http://127.0.0.1:8000/
```

---

## Future Enhancements

- OTP Verification
- Email Notifications
- Face Recognition Authentication
- Aadhaar/National ID Verification
- Election Scheduling
- Multi-Election Support
- Analytics Dashboard
- Mobile Application
- Blockchain-Based Voting
- PDF Result Reports

---

## Learning Outcomes

This project demonstrates practical experience in:

- Django Web Development
- Authentication & Authorization
- CRUD Operations
- Database Design
- Session Management
- Form Handling
- Role-Based Access Control
- Secure Web Application Development
- SQLite Database Integration
- Responsive Web Design

---

## License

This project is licensed under the MIT License.

---

## Author

**Abisekha Melfin V**

IT Engineer | Full Stack Developer | AI & Machine Learning Enthusiast

**Skills:** Django • Python • HTML • CSS • Bootstrap • JavaScript • SQLite • MySQL • REST APIs • Git
