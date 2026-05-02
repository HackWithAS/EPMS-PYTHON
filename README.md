# 💼 Employee Payroll Management System

A web-based payroll and workforce management application developed using **Python, Streamlit, and MySQL** for handling salary processing, employee records, attendance monitoring, and internal application workflows.

This project demonstrates practical implementation of backend logic, database integration, and dashboard-based UI development in a real-world business scenario.

---

## 📌 Project Overview

The system automates payroll and HR-related operations by centralizing employee information, compensation calculations, attendance tracking, and request management into one platform.

---

## 👨‍💼 Administrator Functions

* 🔐 Register and authenticate admin accounts
* ➕ Add new employee profiles
* ✏️ Edit existing employee details
* ❌ Remove employee records
* 📋 Access full employee database
* 📊 Generate salary summaries and payroll reports
* 📨 Review employee applications
* ✅ Approve or reject submitted requests
* 🛠 Manage organization-wide payroll operations

---

## 👨‍🔧 Employee Functions

* 🔑 Secure employee login
* 👤 View profile and employment details
* 💰 Access salary breakdown
* 🔄 Update account password
* 📝 Submit leave or general requests
* 📍 Track request/application status
* 🕒 Mark attendance daily
* 📅 Review attendance history

---

## 🧮 Payroll Logic

Salary is processed automatically using the following rules:

* 🏠 HRA = 20% of Base Salary
* 📈 DA = 10% of Base Salary
* 💸 Tax = 10% of Gross Salary
* 💵 Net Salary = Gross Salary − Tax

---

## 🛠 Technology Stack

* 🐍 Python
* 🎨 Streamlit
* 🗄 MySQL
* 📊 Pandas
* 🔌 MySQL Connector

---

## 📂 Folder Structure

```text id="i9yj1f"
Employee-Payroll-Management-System/
├── Epms.py
├── requirements.txt
├── README.md
└── MySQL Database
```

---

## ⚙️ Setup Instructions

### 📦 Install Dependencies

```bash id="33nwm8"
pip install streamlit mysql-connector-python pandas
```

### 🗃 Create Database

```sql id="px80u7"
CREATE DATABASE Employee_Payroll_System;
```

### ▶️ Run Project

```bash id="f1b4bt"
streamlit run Epms.py
```

---

## 👨‍💻 Author

**Ayush Sharma**

---

## 🚀 Future Improvements

* 📄 Automated Payslip Generation
* 📧 Email Notification Integration
* ☁️ Cloud Deployment
* 🔐 Advanced Role Management
