# 🥪 Hostel Snack Pre-Order System (MVP)

## 📌 Project Overview

A functional MVP of a hostel snack pre-order system that captures real demand before preparation.  
Students select quantities within a deadline, and mess staff view aggregated demand in real time.

This is a front-end prototype built to validate the workflow and product logic — not a production-ready system.

---

## 🎯 Problem Being Solved

Hostel snacks are typically prepared assuming one item per student, which leads to:

- Demand uncertainty  
- Food wastage  
- Student dissatisfaction  
- No structured way to capture extra demand  

This MVP tests a simple rule-based system to move from assumption-driven to demand-driven preparation.

---

## 💡 What This MVP(Minimum Viable Product) Demonstrates

- Role-based login (Student / Mess Staff)
- Snack announcement for next day
- Deadline-based ordering system
- Quantity cap logic (1–3 items)
- Default allocation behavior
- Real-time demand aggregation
- Order summary dashboard for staff

---

## 🖥️ How It Works

### Student Side
- Login as Student
- View tomorrow’s snack
- Select quantity (min 1, max 3)
- Submit before deadline
- Orders are locked after deadline

### Staff Side
- Login as Mess Staff
- Set snack item
- Set order deadline
- View:
  - Total quantity required
  - Number of students ordered

All data is stored locally using browser storage.

---

## 🛠️ Tech Stack (MVP Implementation)

Based on the HTML implementation :contentReference[oaicite:1]{index=1}:

- React 18 (via CDN)
- ReactDOM (UMD build)
- Babel Standalone (in-browser JSX transpiling)
- Vanilla CSS (custom styling)
- Browser LocalStorage (temporary data persistence)
- Single-page application inside one HTML file

No backend or database is used in this prototype.

---

## ⚠️ Important Notes

- This is an AI-assisted MVP built to validate product logic.
- Not production-ready.
- No authentication security.
- No database integration.
- No payment integration.
- Data resets if browser storage is cleared.

The focus is on workflow validation and user experience simulation.

---

## 🚀 Future Improvements

- Backend integration (Node.js / Django)
- Real database (PostgreSQL / MySQL)
- Proper authentication system
- Payment gateway for extra items
- Admin analytics dashboard
- Deployment-ready architecture

---

## 📌 Why This Project Matters

This project demonstrates:

- Product-first thinking
- Translating an operational problem into a digital workflow
- Rule-based system design
- MVP validation approach
- Understanding of role-based UI logic
- Ability to prototype quickly using modern frontend tools

---

## 📄 License

MIT License
