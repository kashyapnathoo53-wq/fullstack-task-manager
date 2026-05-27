# 🚀 Full Stack Task Manager App

A complete Full Stack Task Manager Application built using React, Node.js, Express, Prisma ORM, PostgreSQL, and JWT Authentication.

---

# 📌 Features

## 🔐 Authentication
- User Registration
- User Login
- JWT Token Authentication
- Protected Routes
- Logout Functionality

---

## 📝 Task Management
- Create Task
- View All Tasks
- Update Task
- Delete Task
- User-specific Tasks

---

## 🎨 Frontend Features
- React + Vite
- Axios API Integration
- Toast Notifications
- Responsive UI
- State Management using React Hooks

---

## ⚙ Backend Features
- REST APIs
- Express.js Server
- Prisma ORM
- PostgreSQL Database
- Middleware Authentication
- Error Handling
- Swagger API Documentation

---

# 🛠 Tech Stack

## Frontend
- React.js
- Vite
- Axios
- React Hot Toast

## Backend
- Node.js
- Express.js
- Prisma ORM
- PostgreSQL
- JWT Authentication
- bcrypt.js

---

# 📂 Project Structure

task-manager-project/
│
├── frontend/
│ ├── src/
│ ├── public/
│ └── package.json
│
├── backend/
│ ├── controllers/
│ ├── routes/
│ ├── middleware/
│ ├── prisma/
│ └── package.json

---

# 🚀 API Endpoints

## Auth Routes
- POST /api/v1/auth/register
- POST /api/v1/auth/login

## Task Routes
- GET /api/v1/tasks
- POST /api/v1/tasks
- PUT /api/v1/tasks/:id
- DELETE /api/v1/tasks/:id

---

# 🔑 Authentication

JWT Token-based authentication is implemented.

Protected routes require:

Authorization: Bearer <token>

---

# 📸 Screenshots

(Add your screenshots here later)

---

# 📖 Swagger Documentation

Visit:

http://localhost:5000/api-docs

---

# 👨‍💻 Author

Developed by Kashyap

---

# ⭐ Future Improvements
- Task Status
- Search & Filter
- Dark/Light Theme
- Deployment
- Role-based Access
