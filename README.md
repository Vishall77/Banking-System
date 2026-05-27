<div align="center">

```
██████╗  █████╗ ███╗   ██╗██╗  ██╗██╗███╗   ██╗ ██████╗      
██╔══██╗██╔══██╗████╗  ██║██║ ██╔╝██║████╗  ██║██╔════╝      
██████╔╝███████║██╔██╗ ██║█████╔╝ ██║██╔██╗ ██║██║  ███╗     
██╔══██╗██╔══██║██║╚██╗██║██╔═██╗ ██║██║╚██╗██║██║   ██║     
██████╔╝██║  ██║██║ ╚████║██║  ██╗██║██║ ╚████║╚██████╔╝     
╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝╚═╝╚═╝  ╚═══╝ ╚═════╝      
                                                               
███████╗██╗   ██╗███████╗████████╗███████╗███╗   ███╗        
██╔════╝╚██╗ ██╔╝██╔════╝╚══██╔══╝██╔════╝████╗ ████║        
███████╗ ╚████╔╝ ███████╗   ██║   █████╗  ██╔████╔██║        
╚════██║  ╚██╔╝  ╚════██║   ██║   ██╔══╝  ██║╚██╔╝██║        
███████║   ██║   ███████║   ██║   ███████╗██║ ╚═╝ ██║        
╚══════╝   ╚═╝   ╚══════╝   ╚═╝   ╚══════╝╚═╝     ╚═╝        
```

### 🏦 Full Stack Banking System — Production Deployed

[![Live Demo](https://img.shields.io/badge/🌐_Live_App-Click_Here-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)](https://banking-system-production-262d.up.railway.app/)
[![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-Backend-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![Railway](https://img.shields.io/badge/Deployed_on-Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)](https://railway.app)
[![Status](https://img.shields.io/badge/Status-Live_✅-28a745?style=for-the-badge)]()

<br/>

*" Simulating real-world ATM & online banking — built with security-first architecture "*

<br/>

</div>

---



## 📌 Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)  
- [Key Highlights](#-key-highlights)
- [System Architecture](#-system-architecture)
- [Core Features](#-core-features)
- [Tech Stack](#-tech-stack)
- [Deployment](#-deployment)
- [Email System](#-email-system)
- [Challenges & Solutions](#-challenges--solutions)
- [What This Demonstrates](#-what-this-project-demonstrates)
- [Future Enhancements](#-future-enhancements)
- [About the Developer](#-about-the-developer)

---

## 🧠 Overview

**Banking System** is a production-deployed web application that replicates core banking and ATM workflows. Built with a strong emphasis on **security**, **transaction integrity**, and **scalable backend architecture** — this is not just a CRUD app.

| 🔒 Security | ⚡ Real-Time Ops | ☁️ Cloud Native |
|:-----------:|:----------------:|:---------------:|
| SHA-256 hashing, brute-force lock, session control | Live deposits, withdrawals & transfers | Railway + MySQL, CI/CD via GitHub |

---

## 🌐 Live Demo

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║          Fully live · Auto-deployed · Cloud hosted           ║
╚══════════════════════════════════════════════════════════════╝
```

### 👉 [https://banking-system-production-262d.up.railway.app](https://banking-system-production-262d.up.railway.app)

[![Open App](https://img.shields.io/badge/🚀_Open_Live_App-Click_Here-28a745?style=for-the-badge)](https://banking-system-production-262d.up.railway.app)

</div>

---

## 🚀 Key Highlights

```
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│   🔐  SHA-256 PIN Auth      →   Secure hashed credentials   │
│   💳  Live Transactions     →   Deposit · Withdraw · Send   │
│   📊  Bank Statements       →   Date-wise filtered records  │
│   🚫  Fraud Prevention      →   Account lock + limits       │
│   ☁️  Cloud Deployment      →   Railway + MySQL             │
│   📧  Email Notifications   →   SMTP-based alerts           │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

## 🏗️ System Architecture

```
  ┌──────────────────────────────────┐
  │        🖥️  USER BROWSER          │
  │     HTML · CSS · Jinja2         │
  └─────────────────┬────────────────┘
                    │   HTTP / HTTPS
                    ▼
  ┌──────────────────────────────────┐
  │       ⚙️  FLASK BACKEND          │
  │   Routes · Logic · Sessions     │
  └─────────────────┬────────────────┘
                    │   ORM Layer
                    ▼
  ┌──────────────────────────────────┐
  │       🗃️  SQLALCHEMY ORM         │
  │    Models · Queries · Schema    │
  └─────────────────┬────────────────┘
                    │   SQL Queries
                    ▼
  ┌──────────────────────────────────┐
  │     🛢️  MYSQL — RAILWAY CLOUD    │
  │   Persistent · Relational DB    │
  └──────────────────────────────────┘
```

---

## ⚙️ Core Features

### 👤 Account Management

```
  ✦ Unique account number generation on registration
  ✦ Secure login with full session management
  ✦ Auto account lock after 3 failed PIN attempts
  ✦ PIN recovery via security question
```

### 💰 Banking Operations

```
  ✦ Real-time balance inquiry
  ✦ Deposit & Withdraw — with configurable daily limits
  ✦ Peer-to-peer money transfer
  ✦ Dynamic transaction validation before processing
```

### 📊 Analytics & Records

```
  ✦ Bank statement generation with date-wise filtering

  ┌─────────────────────────────────────────────┐
  │  📥 Deposits  │  📤 Withdrawals  │  🔄 Transfers  │
  └─────────────────────────────────────────────┘
        Sent transactions + Received — all categorized
```

### 🔐 Security Layer

```
  ✦ SHA-256 PIN hashing — no plain-text storage
  ✦ Brute-force lock — timed cooldown after failed attempts
  ✦ Input validation — sanitized on every request
  ✦ Session-based access control — no unauthorized access
```

---

## 🛠️ Tech Stack

| Layer | Technology | Role |
|:-----:|:----------:|:----:|
| 🐍 Backend | **Flask** | Routing, logic, request handling |
| 🛢️ Database | **MySQL (Railway)** | Persistent cloud data storage |
| 🔗 ORM | **SQLAlchemy** | Database abstraction layer |
| 🎨 Frontend | **HTML, CSS, Jinja2** | Dynamic UI templating |
| ☁️ Cloud | **Railway** | Hosting + CI/CD pipeline |
| 📧 Email | **SMTP via Gmail** | Transactional notifications |
| 🔧 Utils | **NumPy, python-dotenv** | Data ops & env config |
| 🚀 Server | **Gunicorn** | Production WSGI server |

---

## 📦 Deployment

```bash
# 🔐 Required Environment Variables
SECRET_KEY        = your_flask_secret_key
DB_HOST           = your_mysql_host
DB_NAME           = your_database_name
DB_USER           = your_db_username
DB_PASSWORD       = your_db_password
SMTP_EMAIL        = your_email@gmail.com
SMTP_PASSWORD     = your_gmail_app_password
```

```
  ✦ Auto-deployed on push to GitHub via Railway CI/CD
  ✦ All credentials secured via environment variables
  ✦ MySQL provisioned as Railway plugin
  ✦ Gunicorn serving as production WSGI server
```

---

## 📧 Email System

| Event | Notification |
|:-----:|:------------:|
| 🆕 New account created | Welcome email sent automatically |
| 🔑 PIN reset requested | Reset confirmation email |

> ⚠️ **Note:** SMTP can be restricted on cloud platforms.  
> For production scale, **SendGrid** or **AWS SES** is recommended over raw SMTP.

---

## 🧩 Challenges & Solutions

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 🚧  CHALLENGE 1 — MySQL Driver Error on Deployment
─────────────────────────────────────────────────────────
  Problem  →  MySQLdb not compatible with Railway env
  Solution →  Switched to pymysql + updated DB URI ✅
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 🚧  CHALLENGE 2 — SMTP Blocked on Railway
─────────────────────────────────────────────────────────
  Problem  →  Default SMTP ports were restricted
  Solution →  Moved to SSL (port 465) + error fallback ✅
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 🚧  CHALLENGE 3 — App Crash After Registration
─────────────────────────────────────────────────────────
  Problem  →  Template rendering failed on new accounts
  Solution →  Fixed with proper error handling in routes ✅
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 📈 What This Project Demonstrates

```
  ◈  Full-stack development from scratch to production
  ◈  Backend architecture design using Flask blueprints
  ◈  Secure auth — hashing, sessions, brute-force protection
  ◈  Relational database modeling with SQLAlchemy ORM
  ◈  Cloud deployment + environment variable management
  ◈  Real-world debugging of production crashes & errors
```

---

## 🔮 Future Enhancements

```
  [ ]  🔑  JWT-based auth          →  API-first architecture
  [ ]  ⚛️   React frontend          →  Better UX & SPA routing
  [ ]  📱  OTP verification        →  2FA on login & transfers
  [ ]  ⚡  Async email (Celery)    →  Background job processing
  [ ]  📊  Analytics dashboard     →  Spending insights & charts
  [ ]  🤖  Fraud Detection         →  Flag unusual patterns (Admin freeze)
```

---

## 👨‍💻 About the Developer

<div align="center">

```
╔═══════════════════════════════════════════╗
║                                           ║
║         👨‍💻  Vishal Baghel                 ║
║                                           ║
║   Aspiring AI/ML Engineer                ║
║   & Full Stack Developer                 ║
║                                           ║
║   Building scalable, real-world apps     ║
║   with strong backend systems            ║
║                                           ║
╚═══════════════════════════════════════════╝
```

</div>

---

<div align="center">

## ⭐ Why This Project Matters

*This project goes beyond a basic CRUD app — it simulates core banking workflows,*  
*integrates real security practices, and runs in a production cloud environment.*  
*A strong portfolio piece for backend and full-stack engineering roles.*

---

**Found it useful? Drop a ⭐ — it means a lot!**

[![GitHub stars](https://img.shields.io/github/stars/Vishall77/Banking-System?style=social)](https://github.com/Vishall77/Banking-System)
[![GitHub forks](https://img.shields.io/github/forks/Vishall77/Banking-System?style=social)](https://github.com/Vishall77/Banking-System/fork)

<br/>

*Crafted with ❤️ by **Vishal Baghel***

</div>
