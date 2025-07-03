# Claim Management System

A simple role-based claim management system built with **Node.js**, **Express**, and **PDF generation**.

---

## ✅ Features
- Secure **login** with hashed passwords and sessions
- Roles: **Employee**, **Manager**, **HR**
- Role-based dashboards & navigation
- Claim approval flow:
  1. Employee ➝ submits claim
  2. Manager ➝ approves manager-level
  3. HR ➝ final approval
- HR-only:
  - Add new users (employees, managers, HR)
  - View user list
- Persistent user & claim storage (JSON-based)
- PDF exports for claims (single & bulk)
- Ready for deployment on **Render** or self-hosted

---

## ✅ Roles & Default Users

| Role     | User ID | Password  |
|----------|---------|-----------|
| HR       | E1003   | password3 |
| Manager  | E1001   | password1 |
| Employee | E1002   | password2 |

---

## ✅ Local Development

```bash
npm install
npm start
