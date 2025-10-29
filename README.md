# B2B Ticket Manager

**A secure, offline-first, B2B support ticket system** — built with HTML, CSS, and JavaScript.  
No backend. No database. No installation. Just open and use.

---

## 🚀 What It Does

**B2B Ticket Manager** is a **complete support ticketing dashboard** for businesses managing customer issues. It lets your team:

- **Create** rich tickets with title, description, customer, priority, status, assignee, and file attachments
- **Track** tickets in real time with live stats (Open, In Progress, Resolved, Total)
- **Collaborate** with inline comments per ticket
- **Search & Filter** by keyword or status
- **Edit / Delete** tickets securely
- **Log in / Register / Reset Password** with client-side SHA-256 hashing
- **Work offline** — all data saved in `localStorage`

---

## 🎯 Key Benefits

| Benefit                | Why It Matters                                                                             |
| ---------------------- | ------------------------------------------------------------------------------------------ |
| **Zero Setup**         | One file. Open in any browser. Done.                                                       |
| **100% Private**       | No server. No cloud. Data stays on the user’s device.                                      |
| **Secure Auth**        | Passwords hashed with SHA-256. "Forgot Password?" with 6-digit reset code (10-min expiry). |
| **Offline-First**      | Works without internet. Perfect for field teams or secure environments.                    |
| **Beautiful UI**       | Tailwind CSS + Heroicons. Professional, responsive, modern.                                |
| **No Dependencies**    | No Node.js, no React, no build step. Pure vanilla JS.                                      |
| **Fast & Lightweight** | < 200 KB. Loads instantly.                                                                 |

---

## ✨ Features

### Authentication

- Register with name, email, password
- Secure login (password always required after logout)
- "Remember my email" option
- **Forgot Password?** → 6-digit code (shown in toast for demo) → reset password

### Ticket Management

- Create / Edit / Delete tickets
- Attach multiple files (images previewed, others downloadable)
- Priority: Low, Medium, High, Critical
- Status: Open, In Progress, Resolved, Closed
- Assignee dropdown (customizable)

### Dashboard

- Real-time stats cards
- Search bar
- Status filter
- Responsive table

### UX / UI

- **No pop-ups** — forms and details appear **inline** in the app
- **Toast notifications** for success/error
- Smooth transitions, no page reloads
- Mobile-friendly

---

## 🛠️ Tech Stack

- **HTML5** – Structure
- **Tailwind CSS** – Styling (via CDN)
- **Vanilla JavaScript** – Logic
- **Web Crypto API** – Password hashing
- **localStorage** – Persistent data

> No backend. No database. No API.

---

## 📂 Project Structure
