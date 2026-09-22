<div align="center">

# 💼 Online Job Portal

### A Full-Featured Web Platform Connecting Job Seekers with Employers

[![PHP](https://img.shields.io/badge/PHP-8.x-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

**A complete job portal solution** where employers post jobs, job seekers apply, and admins manage the entire ecosystem — built with PHP, MySQL, and a responsive front-end.

[📥 Download](#-getting-started) · [🐛 Report Bug](https://github.com/SIRATHNAYAKA/Online-Job-Protal/issues) · [✨ Request Feature](https://github.com/SIRATHNAYAKA/Online-Job-Protal/issues)

</div>

---

## 📑 Table of Contents

<details open>
<summary>Click to expand / collapse</summary>

- [📌 Overview](#-overview)
- [🎯 Key Highlights](#-key-highlights)
- [✨ Features](#-features)
- [🛠 Tech Stack](#-tech-stack)
- [🏗 Architecture](#-architecture)
- [📂 Project Structure](#-project-structure)
- [🗄 Database Schema](#-database-schema)
- [🚀 Getting Started](#-getting-started)
- [🎮 Usage](#-usage)
- [🖼 Screenshots](#-screenshots)
- [🔐 Security Notes](#-security-notes)
- [🔮 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📬 Contact](#-contact)

</details>

---

## 📌 Overview

**Online Job Portal** is a web-based application that bridges the gap between **job seekers** and **employers**. It provides a centralized platform where companies can post job openings, manage applications, and search for talent — while job seekers can create profiles, upload resumes, browse listings, and apply for jobs.

The system is built with **PHP** for server-side logic, **MySQL** for data persistence, and **HTML/CSS/JavaScript** for a responsive, user-friendly interface. It follows a **modular, role-based architecture** with separate dashboards for **Admins**, **Employers**, and **Job Seekers**.

> 💡 **Why this project?** Unlike basic CRUD portals, this system includes role-based access control, resume uploads, application tracking, advanced search filters, and admin analytics — making it a practical, portfolio-ready full-stack web application.

---

## 🎯 Key Highlights

| 🏆 | Highlight |
| :-: | :--- |
| 🔐 | **Role-based authentication** — Admin, Employer, and Job Seeker portals |
| 📄 | **Resume upload & management** — PDF/DOC upload with validation |
| 🔍 | **Advanced job search** — Filter by location, category, type, salary |
| 📊 | **Application tracking** — Employers shortlist/reject; seekers track status |
| 🏢 | **Company profiles** — Employer branding with logo and details |
| 📈 | **Admin analytics** — Reports on jobs, applications, and users |
| 🛡️ | **Secure sessions** — Password hashing, session management, CSRF protection |
| 📱 | **Fully responsive** — Works on desktop, tablet, and mobile |

---

## ✨ Features

### 👤 Job Seeker Features

| Feature | Description |
| :--- | :--- |
| 🆕 **Registration & Login** | Create a free account with email verification |
| 👤 **Profile Management** | Update personal info, skills, education, and experience |
| 📄 **Resume Upload** | Upload resume (PDF/DOC) — visible to employers |
| 🔍 **Browse Jobs** | View all active job listings with pagination |
| 🎯 **Advanced Search** | Filter by keyword, location, category, job type, salary range |
| 📝 **Apply for Jobs** | One-click apply with cover letter |
| 📊 **Application Status** | Track: Applied → Shortlisted → Interview → Selected/Rejected |
| 🔖 **Save Jobs** | Bookmark jobs for later |
| 🔔 **Job Alerts** | Email notifications for matching jobs |

### 🏢 Employer Features

| Feature | Description |
| :--- | :--- |
| 🏢 **Company Profile** | Add company details, logo, website, and description |
| ➕ **Post Jobs** | Create job listings with title, description, requirements, salary |
| 📋 **Manage Listings** | Edit, close, or delete job posts |
| 👥 **View Applications** | See all applicants with resumes and cover letters |
| ✅ **Shortlist / Reject** | Update application status with notes |
| 🔍 **Search Talent** | Browse job seeker profiles and resumes |
| 📈 **Dashboard** | View job post performance and application counts |

### 🛡️ Admin Features

| Feature | Description |
| :--- | :--- |
| 📊 **Admin Dashboard** | Overview of users, jobs, applications, and revenue |
| 👥 **User Management** | View, edit, activate/deactivate, or delete accounts |
| 📋 **Job Moderation** | Approve, reject, or flag job listings |
| 🏢 **Company Management** | Verify and manage employer accounts |
| 📑 **Reports** | Generate reports for jobs, applications, and user activity |
| ⚙️ **Settings** | Configure site title, email, and other parameters |
| 🔒 **Role Management** | Assign permissions to different user roles |

### ⚙️ Technical Features

- **PDO / MySQLi** — Prepared statements to prevent SQL injection
- **Password Hashing** — `password_hash()` with bcrypt
- **Session Management** — Secure sessions with timeout and regeneration
- **File Upload Validation** — MIME type, size, and extension checks
- **Email Notifications** — PHP `mail()` or PHPMailer for alerts
- **Pagination** — Efficient loading of large datasets
- **Responsive Design** — Bootstrap 5 grid and components
- **CSRF Protection** — Tokens on all forms

---

## 🛠 Tech Stack

<div align="center">

| Category | Technology |
| :--- | :--- |
| **Front-end** | HTML5, CSS3, JavaScript, Bootstrap 5 |
| **Back-end** | PHP 8.x (OOP + procedural mix) |
| **Database** | MySQL 8.0 |
| **DB Connectivity** | PDO (PHP Data Objects) |
| **Server** | Apache (XAMPP / WAMP / LAMP) |
| **Email** | PHPMailer / PHP mail() |
| **PDF Generation** | TCPDF / FPDF *(optional for reports)* |
| **Version Control** | Git + GitHub |
| **IDE** | VS Code / PhpStorm / Sublime Text |

</div>

---

## 🏗 Architecture

The application follows a **classic 3-tier web architecture**:
