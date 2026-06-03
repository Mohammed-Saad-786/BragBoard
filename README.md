
<div align="center">
   <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=56&pause=1500&color=3B82F6&center=true&vCenter=true&width=1200&lines=Celebrate+Achievements+%F0%9F%8E%89;Recognize+Outstanding+Contributions+%F0%9F%8C%9F;Strengthen+Workplace+Culture+%F0%9F%A4%9D;Built+with+React+%2B+FastAPI+%E2%9A%A1;BragBoard+%E2%80%94+Peer+Recognition+Platform+%F0%9F%9A%80" alt="Typing SVG" /> </div>
<div align="center">
<br>

![Stars](https://img.shields.io/github/stars/Mohammed-Saad-786/BragBoard?style=for-the-badge)
![Forks](https://img.shields.io/github/forks/Mohammed-Saad-786/BragBoard?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/Mohammed-Saad-786/BragBoard?style=for-the-badge)
![License](https://img.shields.io/github/license/Mohammed-Saad-786/BragBoard?style=for-the-badge)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Mohammed-Saad-786.BragBoard)
### 🚀 Building a Culture of Recognition Through Technology

A modern full-stack employee engagement platform that enables organizations to celebrate achievements, recognize contributions, and strengthen workplace culture through peer-to-peer appreciation.

</div>

---

## 📖 Overview

BragBoard is a workplace recognition platform designed to encourage positive employee engagement through peer-to-peer appreciation.

Employees can create shoutouts, recognize colleagues, interact through comments and reactions, and contribute to a culture of recognition and motivation within their organization.

The platform is built using modern technologies including React, FastAPI, SQLAlchemy, PostgreSQL, and JWT Authentication.

---

## 🏢 Business Problem

In modern workplaces, employee contributions and achievements often go unnoticed due to busy schedules, distributed teams, and limited opportunities for recognition.

Organizations commonly face the following challenges:

- Lack of a centralized platform for employee recognition
- Employee achievements are often overlooked or underappreciated
- Reduced employee engagement and workplace morale
- Limited peer-to-peer appreciation and collaboration
- Difficulty tracking recognition trends and team contributions
- Lack of visibility into employees making a positive impact

As a result, employees may feel less motivated, less connected to their teams, and less valued within the organization, ultimately affecting productivity, retention, and workplace culture.

---

## 💡 Solution

BragBoard provides a centralized peer-recognition platform that enables employees to appreciate and celebrate each other's contributions.

The platform empowers organizations by:

- Creating a culture of appreciation and recognition
- Increasing employee engagement and morale
- Providing visibility into employee achievements
- Encouraging collaboration across teams and departments
- Enabling administrators to monitor engagement trends and recognition metrics
- Building a more connected and motivated workforce

Through shoutouts, reactions, comments, and analytics, BragBoard transforms recognition into a measurable and impactful part of workplace culture.

---

## ✨ Key Features

### 🔐 Authentication & User Management

- Secure User Registration & Login
- JWT Authentication
- Password Encryption using Bcrypt
- Forgot Password Workflow
- Reset Password Functionality
- User Profile Management
- Role-Based Access Control (Employee/Admin)

### 🎉 Recognition System

- Send Recognition Shoutouts
- Mention & Tag Colleagues
- Organization-Wide Recognition Feed
- Department-Based Recognition
- Recognition History Tracking

### 💬 Social Engagement

- Like, Clap & Star Reactions
- Comment System
- Interactive Feed Experience
- Community Recognition Features

### 🛡️ Administration & Moderation

- Admin Dashboard
- User Monitoring
- Content Moderation
- Recognition Analytics
- Reporting & Audit Logs

### 📊 Analytics

- Recognition Metrics
- Top Contributors
- Department Insights
- Employee Engagement Tracking

---

## 🛠️ Tech Stack

### Frontend

| Technology | Version |
|------------|----------|
| React | 19 |
| Vite | 7 |
| TailwindCSS | 4 |
| React Router DOM | 7 |
| Framer Motion | Latest |
| React Icons | Latest |

### Backend

| Technology | Purpose |
|------------|---------|
| FastAPI | REST API Development |
| Uvicorn | ASGI Server |
| SQLAlchemy | ORM |
| Pydantic | Data Validation |
| Python-Jose | JWT Authentication |
| Passlib (Bcrypt) | Password Hashing |

### Database

- SQLite (Development)
- PostgreSQL (Production)

---

## 🏗️ System Architecture

```text
┌───────────────────────────┐
│      React Frontend       │
│     Vite + TailwindCSS    │
└─────────────┬─────────────┘
              │ REST API
              ▼
┌───────────────────────────┐
│      FastAPI Backend      │
│ JWT Authentication        │
│ SQLAlchemy ORM            │
└─────────────┬─────────────┘
              │
              ▼
┌───────────────────────────┐
│ PostgreSQL / SQLite DB    │
└───────────────────────────┘
```

---

## 📂 Repository Structure

```text
📦 BragBoard
┣ 📂 backend
┃ ┣ 📂 app
┃ ┃ ┣ 📂 routers
┃ ┃ ┃ ┣ 📜 __init__.py
┃ ┃ ┃ ┣ 📜 auth.py
┃ ┃ ┃ ┣ 📜 shoutouts.py
┃ ┃ ┃ ┗ 📜 users.py
┃ ┃ ┣ 📜 __init__.py
┃ ┃ ┣ 📜 admin.py
┃ ┃ ┣ 📜 database.py
┃ ┃ ┣ 📜 deps.py
┃ ┃ ┣ 📜 main.py
┃ ┃ ┣ 📜 models.py
┃ ┃ ┣ 📜 schemas.py
┃ ┃ ┗ 📜 security.py
┃ ┣ 📂 uploads
┃ ┣ 📜 check_db.py
┃ ┣ 📜 fix_password.py
┃ ┣ 📜 normalize_emails.py
┃ ┣ 📜 requirements.txt
┃ ┗ 📜 update_db.py
┃
┣ 📂 frontend
┃ ┣ 📂 src
┃ ┃ ┣ 📂 Components
┃ ┃ ┃ ┣ 📂 Assests
┃ ┃ ┃ ┣ 📂 LoginRegister
┃ ┃ ┃ ┃ ┣ 📜 LoginRegister.css
┃ ┃ ┃ ┃ ┗ 📜 LoginRegister.jsx
┃ ┃ ┃ ┣ 📜 AdminDashboard.jsx
┃ ┃ ┃ ┣ 📜 EditProfile.jsx
┃ ┃ ┃ ┣ 📜 FeedPage.jsx
┃ ┃ ┃ ┣ 📜 Navbar.jsx
┃ ┃ ┃ ┣ 📜 Profile.jsx
┃ ┃ ┃ ┣ 📜 ProfilePage.jsx
┃ ┃ ┃ ┣ 📜 Shoutout.jsx
┃ ┃ ┃ ┣ 📜 ShoutoutFeed.jsx
┃ ┃ ┃ ┗ 📜 SuccessPage.jsx
┃ ┃ ┣ 📂 assets
┃ ┃ ┣ 📜 App.css
┃ ┃ ┣ 📜 App.jsx
┃ ┃ ┣ 📜 index.css
┃ ┃ ┗ 📜 main.jsx
┃ ┣ 📜 package.json
┃ ┗ 📜 vite.config.js
┃
┣ 📜 .gitignore
┗ 📜 README.md
```

---

## 🔒 Security Features

- Bcrypt Password Hashing
- JWT-Based Authentication
- Protected API Endpoints
- Token Expiration Handling
- Role-Based Authorization
- SQL Injection Protection via SQLAlchemy
- Pydantic Input Validation
- Secure User Data Handling

---

## 📌 API Endpoints

### Authentication

| Method | Endpoint |
|----------|----------|
| POST | `/auth/register` |
| POST | `/auth/login` |
| POST | `/auth/forgot-password` |
| POST | `/auth/reset-password` |

### Users

| Method | Endpoint |
|----------|----------|
| GET | `/users/me` |
| PUT | `/users/me` |

### Shoutouts

| Method | Endpoint |
|----------|----------|
| POST | `/shoutouts` |
| GET | `/shoutouts` |

---

## 🚀 Getting Started

### Prerequisites

- Node.js v18+
- Python v3.8+
- Git

### Clone Repository

```bash
git clone https://github.com/Mohammed-Saad-786/BragBoard.git
cd BragBoard
```

### Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/macOS
source venv/bin/activate

pip install -r requirements.txt

uvicorn app.main:app --host 0.0.0.0 --port 9000 --reload
```

Backend:

```text
http://localhost:9000
```

Swagger Docs:

```text
http://localhost:9000/docs
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend:

```text
http://localhost:5173
```

---

## 🚧 Project Status

### ✅ Completed

- User Authentication
- User Registration & Login
- JWT Security
- Profile Management
- Database Integration
- Frontend Routing
- Admin Foundation

### 🚀 Upcoming

- Advanced Shoutout Features
- Reactions & Comments
- Analytics Dashboard
- Moderation Tools
- Reporting System

---

## 🎯 Learning Outcomes

This project demonstrates:

- Full Stack Development
- React Frontend Engineering
- FastAPI Backend Development
- REST API Design
- JWT Authentication
- Database Design & ORM Usage
- Secure Coding Practices
- Role-Based Access Control
- Modern UI/UX Development

---

<div align="center">

## 🌟 Why BragBoard?

BragBoard was built to solve a real workplace challenge — ensuring employee achievements never go unnoticed.

By combining modern full-stack technologies with an intuitive user experience, the platform helps organizations foster recognition, strengthen team culture, and improve employee engagement.

</div>

---

<div align="center">

## 🤝 Connect With Me 
<p> Building impactful software, exploring AI, and creating modern full-stack applications. </p> <a href="https://github.com/Mohammed-Saad-786" target="_blank"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/> </a> <a href="https://www.linkedin.com/in/mohammed-saad-tech/" target="_blank"> <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/> </a> <a href="mailto:555mohammedsaad@gmail.com"> <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/> </a> <br><br>

### ⭐ Support This Project

If you found BragBoard useful, consider giving it a star.

<a href="https://github.com/Mohammed-Saad-786/BragBoard">
  <img src="https://img.shields.io/badge/⭐%20Star%20This%20Repo-yellow?style=for-the-badge"/>
</a>

</div>
