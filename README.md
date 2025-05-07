# 🏫 SpellAcademy – AI-Powered School Management System

SpellAcademy is a modern school management system powered by AI, built to simplify academics, communication, visitor tracking, and financial operations for Rwandan schools and beyond.

---

## 🎯 Purpose

To centralize and automate school operations using modern web tools and AI for lesson planning, grade tracking, behavior management, and communication.

---

## 🛠️ Tech Stack

| Layer | Technology |
|------|------------|
| Frontend | React (Node.js), TypeScript |
| Authentication | **Clerk.com** |
| Database & Storage | **Supabase** (PostgreSQL + File Storage) |
| AI Tools | Trey AI, Lovable, Casta, ChatGPT, AI.AI |
| Dev Environment | Trey AI, Cursor AI, Lovable |
| Routing | React Router v6 |
| Version Control | Git & GitHub |
| State Management | Coming Soon (Redux / Context API) |
| QA / Bug Tracking | JIRA |

---

## 👥 User Roles & Responsibilities

- **Admin** – Oversees all system activities
- **Teacher** – Uploads assignments, grades, manages lessons & timetable
- **Student** – Views materials, assignments, grades
- **Parent** – Reviews child’s performance & communicates with teachers
- **Librarian** – Manages book lending/return system
- **Accountant** – Manages fees, salaries, transactions
- **Disciplinary Officer** – Tracks and deducts behavior points
- **Head of Studies (Headteacher)** – Reviews and adjusts student grades, manages teachers, subjects, lesson plans, and timetables
- **Gate Keeper** – Registers/logs visitors (name, ID, purpose, time)

---

## 📚 Core Features

✅ = Completed or In Progress

| Category | Feature |
|---------|---------|
| ✅ Authentication | Clerk-based registration & login |
| ✅ Role-Based Access | Role-based dashboard access |
| ✅ Assignments | Upload, submit, track assignments |
| ✅ Grading | Grade tracking + AI-generated report cards |
| ✅ Curriculum Upload | AI-generated schemes of work + lessons |
| ✅ Attendance | Attendance marking per class |
| ✅ Discipline | Point-based behavior tracking system |
| ✅ Visitors | Gatekeeper logs visitors with ID & purpose |
| ✅ Library | Borrowed/returned book tracking |
| ✅ Accounting | School fee tracking, salaries, expenses |
| ✅ Notifications | SMS/Email alerts for parents/staff |
| ✅ Payments | MTN MoMo, Bank, Western Union, Crypto |
| ✅ AI Assistant | ChatGPT answers school FAQs |
| ✅ Headteacher Tools | Teacher management, timetable builder, report verification |
| ✅ Communication | Internal messaging & parent-teacher chat |

---

## 🧠 AI Use Cases

- Generate lesson plans from uploaded curriculum (Govt of Rwanda)
- ChatGPT Assistant to answer FAQs
- Student performance insights (future)
- Prompt-based code generation with Trey AI, Lovable, Casta

---

## 📅 Milestone-Based Roadmap

### Phase 1: Initial Setup
- [x] React + TypeScript + Clerk
- [x] Setup Supabase database
- [x] Setup folder structure & GitHub
- [ ] Define user roles & protected routes
- [ ] Setup role-based layouts

### Phase 2: Core Modules
- [ ] Auth (SignIn, SignUp, RBAC)
- [ ] Assignment + Grading
- [ ] Class Schedules & Timetables
- [ ] Curriculum Upload & AI Scheme Generation
- [ ] Student Dashboard

### Phase 3: Specialized Roles
- [ ] Headteacher Dashboard (grades, teacher mgmt, schedule)
- [ ] Disciplinary Dashboard (points, student logs)
- [ ] Accountant Dashboard (transactions, payment logs)
- [ ] Gatekeeper Panel (visitor logs)
- [ ] Parent Communication UI

### Phase 4: Finalization
- [ ] AI Assistant (ChatGPT)
- [ ] Notification System (SMS/Email)
- [ ] Full QA with JIRA
- [ ] Launch & Deployment

---

## 📁 Folder Structure

spellacademy/
├── public/
├── src/
│   ├── assets/                  # Images, icons, etc.
│   ├── components/             # Reusable UI components (e.g. Navbar, Sidebar)
│   ├── layouts/                # Page layouts based on user role (AdminLayout, TeacherLayout, etc.)
│   ├── pages/                  # Pages per role or feature
│   │   ├── admin/
│   │   ├── accountant/
│   │   ├── auth/               # SignIn, SignUp, Clerk profile
│   │   ├── dashboard/          # General dashboards (e.g. role-specific)
│   │   ├── disciplinary/
│   │   ├── gatekeeper/
│   │   ├── headteacher/
│   │   ├── librarian/
│   │   ├── parent/
│   │   ├── student/
│   │   ├── teacher/
│   ├── services/               # Supabase, Clerk, API helpers
│   ├── context/                # React context for state (AuthContext, RoleContext, etc.)
│   ├── routes/                 # Protected Routes, RoleBasedRoutes
│   ├── types/                  # Custom TypeScript types & interfaces
│   ├── utils/                  # Helper functions (formatDate, etc.)
│   ├── ai/                     # AI prompt logic and integrations (ChatGPT, Trey AI, etc.)
│   ├── App.tsx
│   ├── index.tsx
├── .env                        # Environment variables (Clerk, Supabase, etc.)
├── package.json
├── README.md
