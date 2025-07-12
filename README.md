# 📚 Online Library System

A full-stack web-based application that simulates a real-world library management system. Built using **Node.js**, **Express.js**, **Handlebars (HBS)**, and integrated with a backend database, this system allows users to browse, borrow, and return books online. It is designed to serve both students and administrators with role-specific functionality.

---

## 📘 Introduction

The **Online Library System** is developed as part of a DBMS course project to digitize the core functionalities of a physical library. It manages books, users, and transactions such as borrowing and returning books in a secure and user-friendly way. It serves as a foundational system for academic institutions looking to automate library operations.

---

## 🎯 Purpose

This project aims to:
- 💡 Replace traditional paper-based library records with an efficient online system.
- 🔐 Implement role-based access (Admin and User).
- 📚 Maintain book inventory and borrowing history using structured DBMS operations.
- ⚙️ Demonstrate CRUD operations, session handling, and dynamic rendering using Handlebars.

---

## ✨ Features

### 👤 User Side
- 🔍 **Search Books** by title, author, or category.
- 📖 **View Book Details** like availability, description, and ISBN.
- 📥 **Borrow/Return Books** (limited by rules set in the backend).
- 📋 **Borrowing History** to track user activity.

### 🛠️ Admin Side
- ➕ **Add/Edit/Delete Books** from the catalog.
- 👥 **Manage Users** and borrowing limits.
- 📊 **View Borrow Reports** and late return statistics.

### 🔐 Authentication
- Session-based login/logout for users and admins.
- Flash messages for login success/failure or form errors.

---

## ⚙️ Setup Instructions

### 📦 Prerequisites
Ensure you have the following installed:
- Node.js
- npm
- MySQL / MongoDB (depending on your DB setup)

---

### 🛠️ Installation Steps

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/Online-Library-System.git
cd Online-Library-System

# 2. Install project dependencies
npm install

# 3. Set up your database connection
# (Edit db.js or config.js depending on your structure)

# 4. Start the server
npm start
