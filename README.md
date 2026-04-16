<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,100:8b5cf6&height=200&section=header&text=Student%20Management%20System&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Academic%20Platform%20Powered%20by%20Flask%20%2B%20Next.js&descAlignY=58&descColor=e0e7ff" width="100%"/>

<br/>

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-REST%20API-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![Next.js](https://img.shields.io/badge/Next.js-14-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![JWT](https://img.shields.io/badge/JWT-Auth-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io)

<br/>

[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)]()
[![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=flat-square)]()
[![by Muzammil](https://img.shields.io/badge/Author-Muzammil%20Hussain-6366f1?style=flat-square)]()

<br/>

> **A production-grade, role-based academic management platform** — digitizing student records, teacher data, attendance workflows, and admin operations in one unified system.

<br/>

[🚀 Live Demo](#) · [📖 Documentation](#installation) · [🐛 Report Bug](../../issues) · [💡 Request Feature](../../issues)

<br/>

</div>

---

## 📸 Product Gallery

---

### 🔐 Authentication

| Login Page | Sign Up Page |
|:-:|:-:|
| ![Login Page](docs/images/auth-login.png) | ![Sign Up Page](docs/images/auth-signup.png) |
| *Secure JWT-based login* | *New admin registration* |

---

### 🖥️ Admin Dashboard

| Main Dashboard | Navigation & Sidebar |
|:-:|:-:|
| ![Admin Dashboard](docs/images/admin-dashboard.png) | ![Admin Navigation](docs/images/admin-navigation.png) |
| *Real-time overview of all modules* | *Fast sidebar navigation* |

---

### 👨‍🎓 Student Management

| Students List | Add Student | Edit Student |
|:-:|:-:|:-:|
| ![Students List](docs/images/students-list.png) | ![Add Student Form](docs/images/students-add-form.png) | ![Edit Student Form](docs/images/students-edit-form.png) |
| *All student records* | *Add new student* | *Update student info* |

---

### 👩‍🏫 Teacher Management

| Teachers List | Add Teacher | Edit Teacher |
|:-:|:-:|:-:|
| ![Teachers List](docs/images/teachers-list.png) | ![Add Teacher Form](docs/images/teachers-add-form.png) | ![Edit Teacher Form](docs/images/teachers-edit-form.png) |
| *Full teacher directory* | *Create teacher record* | *Update teacher info* |

---

### 📋 Attendance Management

| Attendance Overview | Mark Attendance |
|:-:|:-:|
| ![Attendance Overview](docs/images/attendance-overview.png) | ![Mark Attendance](docs/images/attendance-mark-form.png) |
| *History & summary view* | *Daily attendance marking* |

---

### 🎬 Full Demo Video

<div align="center">

> Watch the complete platform walkthrough — login → dashboard → students → teachers → attendance

[![Watch Full Demo Video](https://img.shields.io/badge/▶%20Watch%20Full%20Demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/vZpDi85lj10)

</div>

---

## 🧩 Why This Project Exists

> Most educational institutes still manage students and attendance **manually** — leading to chaos, errors, and wasted time.

<div align="center">

| ❌ Old Way | ✅ With SMS |
|:---|:---|
| Manual registers & paper records | Centralized digital database |
| Data duplication & inconsistencies | Single source of truth |
| Slow attendance reporting | Real-time tracking & history |
| No access control | Role-based JWT authentication |
| Scattered teacher & student data | Unified admin dashboard |

</div>

---

## ✨ Features at a Glance

<details open>
<summary><b>🔐 Authentication & Security</b></summary>

- JWT-based secure login flow
- Password hashing with `bcrypt`
- Protected API routes for all sensitive operations
- Token-based session management on frontend

</details>

<details open>
<summary><b>👨‍🎓 Student Management</b></summary>

- Add students with full academic profiles
- Update, delete, and fetch student records
- Clean table/list views in admin panel

</details>

<details open>
<summary><b>👩‍🏫 Teacher Management</b></summary>

- Create and maintain teacher records
- Manage subject assignments
- Update or remove teacher entries from directory

</details>

<details open>
<summary><b>📋 Attendance Management</b></summary>

- Mark daily attendance per student per date
- Track present / absent status
- View complete attendance history via API and UI

</details>

<details open>
<summary><b>🖥️ Admin Dashboard</b></summary>

- Unified admin panel for all operations
- Fast navigation between modules
- Form-driven CRUD workflows

</details>

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────┐
│                   FRONTEND LAYER                        │
│          Next.js 14 + TypeScript + Tailwind CSS         │
│              shadcn/ui · Radix UI Components            │
└────────────────────────┬────────────────────────────────┘
                         │  HTTP / JSON (REST API)
                         ▼
┌─────────────────────────────────────────────────────────┐
│                   BACKEND LAYER                         │
│            Flask REST API + JWT Auth                    │
│        SQLAlchemy ORM · Marshmallow Schemas             │
│          Flask-Bcrypt · Flask-CORS · PyMySQL            │
└────────────────────────┬────────────────────────────────┘
                         │  SQL Queries
                         ▼
┌─────────────────────────────────────────────────────────┐
│                   DATABASE LAYER                        │
│                  MySQL 8.0 Database                     │
│                  sms_task1 Schema                       │
└─────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

<div align="center">

### Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

</div>

---

## 📁 Project Structure

```
SMS-Frontend-Backend/
│
├── 📂 BackEnd/
│   ├── app.py                    # Flask app entry point
│   ├── requirements.txt          # Python dependencies
│   └── src/
│       ├── __init__.py           # App factory & config
│       ├── extentions.py         # Flask extensions init
│       ├── models/               # SQLAlchemy DB models
│       ├── routers/              # API route handlers
│       │   ├── auth_router.py
│       │   ├── students_router.py
│       │   ├── teachers_router.py
│       │   ├── attendance_router.py
│       │   └── admin_router.py
│       └── schemas/              # Marshmallow serializers
│
└── 📂 FrontEnd/
    ├── app/                      # Next.js App Router pages
    ├── components/               # Reusable UI components
    ├── hooks/                    # Custom React hooks
    ├── lib/                      # Utilities & API helpers
    └── package.json
```

---

## ⚡ Quick Start

### Prerequisites

Make sure you have the following installed:

| Tool | Version |
|------|---------|
| Python | 3.10+ |
| Node.js | 18+ |
| MySQL | 8.0+ |
| npm / pnpm | Latest |

---

### Step 1 — Clone the Repository

```bash
git clone https://github.com/your-username/SMS-Frontend-Backend.git
cd SMS-Frontend-Backend
```

---

### Step 2 — Backend Setup

```bash
cd BackEnd

# Create virtual environment
python -m venv .venv

# Activate — Windows
.\.venv\Scripts\Activate.ps1

# Activate — macOS/Linux
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

---

### Step 3 — Database Setup

```sql
-- Run in MySQL client
CREATE DATABASE sms_task1;
```

Then update the DB URI in `BackEnd/src/__init__.py`:

```python
# Replace with your MySQL credentials
app.config['SQLALCHEMY_DATABASE_URI'] = 'sqlite:///database.db'
```

---

### Step 4 — Frontend Setup

```bash
# From project root
cd FrontEnd

npm install
# or
pnpm install
```

Create `.env.local` file in FrontEnd folder:

```env
NEXT_PUBLIC_API_BASE_URL=http://localhost:5000/api
```

---

### Step 5 — Run the Application

**Terminal 1 — Start Backend:**
```bash
cd BackEnd
python app.py
# Running on http://localhost:5000
```

**Terminal 2 — Start Frontend:**
```bash
cd FrontEnd
npm run dev
# Running on http://localhost:3000
```

🎉 **Open [http://localhost:3000](http://localhost:3000) in your browser!**

---

## 🔌 API Reference

All routes are prefixed with `/api`

| Module | Prefix | Description |
|--------|--------|-------------|
| Auth | `/api/auth` | Login, token management |
| Students | `/api/students` | CRUD for student records |
| Teachers | `/api/teachers` | CRUD for teacher records |
| Attendance | `/api/attendance` | Mark & view attendance |
| Admin | `/api/admin` | Admin management |

---

## 🔧 Troubleshooting

<details>
<summary><b>⚠️ Hydration Warning in Frontend</b></summary>

- Test in Incognito / Private mode
- Temporarily disable browser extensions

</details>

<details>
<summary><b>⚠️ CORS / API Connectivity Issue</b></summary>

- Confirm backend is running on port `5000`
- Check `NEXT_PUBLIC_API_BASE_URL` matches backend URL exactly

</details>

<details>
<summary><b>⚠️ MySQL Connection Error</b></summary>

- Verify MySQL service is running
- Confirm `sms_task1` database exists
- Double-check credentials in `BackEnd/src/__init__.py`

</details>

---

## 🔒 Security Note

> ⚠️ Current config has **JWT secret** and **DB URI hardcoded** for development.  
> Before deploying to production, move all sensitive values to environment variables (`.env`).

---

## 🗺️ Roadmap & Future Vision

### ✅ Currently Implemented

- [x] JWT Authentication & bcrypt password hashing
- [x] Student CRUD — full profile management
- [x] Teacher CRUD — directory & subject management
- [x] Attendance Tracking — mark & view history
- [x] Admin Dashboard — unified control panel
- [x] REST API with modular router structure

---

### 🔰 Phase 2 — Coming Soon (Basic Enhancements)

- [ ] Environment-based config via `.env`
- [ ] Role-based UI route guards on frontend
- [ ] **📊 Reports & Analytics** — attendance %, monthly summaries, PDF export
- [ ] **🔍 Search & Filter** — find students by name, class, or roll number
- [ ] **📁 Student Result Management** — enter marks, generate result cards
- [ ] **🌙 Dark Mode** — light/dark theme toggle
- [ ] **📤 Bulk Import via Excel/CSV** — add multiple students at once
- [ ] Unit & integration tests
- [ ] Docker deployment setup
- [ ] Swagger / OpenAPI documentation

---

### 🟡 Phase 3 — Growth Features (Mid Term)

- [ ] **👨‍👩‍👧 Parent Portal** — parents view child's attendance & results
- [ ] **📧 Email Notifications** — auto email to parents on absence
- [ ] **🏫 Multi-Class & Section Support** — manage multiple classes simultaneously
- [ ] **📅 Timetable Management** — weekly class schedule builder
- [ ] **💳 Fee Management** — fee records, due dates, payment history tracking
- [ ] **📱 Fully Responsive Mobile UI** — optimized for all screen sizes

---

### 🤖 Phase 4 — AI-Powered Features (Advanced)

> *Powered by LangChain · LangGraph · Generative AI*

- [ ] **🤖 AI Admin Chatbot** — ask *"Who had less than 50% attendance this month?"* and get instant answers
- [ ] **📈 Dropout Risk Prediction** — AI flags students at risk based on attendance patterns
- [ ] **🧠 Smart Report Generation** — generate reports using natural language commands
- [ ] **📝 Auto Performance Analysis** — AI identifies weak areas per student and suggests improvements
- [ ] **🗣️ Voice Attendance** — mark attendance via voice commands

---

### 🏆 Phase 5 — SaaS & Scale (Long Term Vision)

- [ ] **🏫 Multi-School SaaS Platform** — onboard multiple institutions on one platform
- [ ] **💰 Subscription Tiers** — Free / Basic / Pro plans for institutes
- [ ] **📲 Mobile App** — React Native iOS & Android app
- [ ] **📊 Super Admin Dashboard** — platform-wide analytics across all schools
- [ ] **🔗 Third-Party Integrations** — connect with LMS platforms and government portals

---

> 💡 **This project is actively growing.** New features are added regularly based on real institute needs and community feedback. Star ⭐ the repo to stay updated!

---

## 👨‍💻 Author

<div align="center">

<img src="https://avatars.githubusercontent.com/your-username" width="100" style="border-radius:50%"/>

### Muzammil Hussain

*AI & Backend Developer | Generative AI | Agentic AI Systems*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muzammal-hussain-ai-developer)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/muzammaldeveloper)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muzammaldeveloper258rb@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,100:8b5cf6&height=100&section=footer" width="100%"/>

**⭐ If this project helped you, please give it a star! It means a lot.**

*Built with ❤️ by Muzammil Hussain — Pakistan 🇵🇰*

</div>
