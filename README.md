# Task Manager

## 📌 Overview

This is a simple **Task Manager** application built with a **NestJS backend (GraphQL API)** and a **React frontend**. It allows users to create, update, delete, and view tasks. The project follows best practices for validation, error handling, and UI feedback.

## 🚀 Features

- **CRUD Operations**: Create, Read, Update, Delete tasks
- **GraphQL API**: NestJS backend with MongoDB
- **Input Validation**: Zod & React Hook Form
- **Error Handling**: Proper API and UI validation messages
- **UI Enhancements**:
  - Success modal after creating a task
  - Confirmation modal before deleting a task
  - Material UI for styling
- **State Management**: Apollo Client for GraphQL cache updates

---

## 🛠️ Tech Stack

### **Backend (NestJS + GraphQL)**

- **NestJS** (with GraphQL Apollo Server)
- **MongoDB** (Mongoose for database interaction)
- **TypeScript**
- **Zod** (for schema validation)
- **Apollo Server Express**

### **Frontend (React + Apollo Client)**

- **React** (React Hook Form for form handling)
- **Apollo Client** (GraphQL state management)
- **Material UI** (UI components)
- **TypeScript**

---

## ⚙️ Setup Instructions

### **🔹 1️⃣ Backend Setup**

#### **Prerequisites:** Ensure you have **Node.js**, **MongoDB**, and **npm** installed.

1. Navigate to the backend folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Copy the example `.env` file:
   ```bash
   cp .env.example .env
   ```
4. Update `.env` with your **MongoDB connection string**:
   ```env
   MONGO_URI=mongodb://localhost:27017/task-manager
   PORT=4200
   ```
5. Start the backend server:
   ```bash
   npm run start
   ```
6. Open **GraphQL Playground** at: [http://localhost:4200/graphql](http://localhost:4200/graphql)

---

### **🔹 2️⃣ Frontend Setup**

1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend application:
   ```bash
   npm start
   ```
4. Open [**http://localhost:5173/**](http://localhost:5173/) in your browser.

---

## 📁 Project Structure

```
task-manager/
│── backend/        # NestJS GraphQL API
│── frontend/       # React app
│── README.md       # Documentation
```

---

## ✅ Assumptions & Decisions

- Used **Apollo Client cache updates** instead of refetching data.
- Used **React Hook Form & Zod** for efficient form validation.
- Implemented **Material UI components** for better UI/UX.
- Used **GraphQL Mutations & Queries** instead of REST.

---

## 📝 `.env.example`

```env
MONGO_URI=mongodb://localhost:27017/task-manager
PORT=4200
```

> ⚠️ **Make sure to create a real **``** file before running the application!**

---

## 📦 Submission Instructions

1. Ensure your GitHub repository is **private** and follows the correct structure.
2. Run the following command in your project root to create the Git bundle:
   ```bash
   git bundle create task-manager.bundle --all
   ```
3. Verify your bundle by cloning it in a separate directory:
   ```bash
   git clone task-manager.bundle verify-folder
   ```
4. If everything works, **submit **``** through the provided form.**

---

## 🎯 Next Steps

- ✅ Implement authentication (JWT for user login & protected tasks)
- ✅ Enhance UI with animations & more detailed task views

---

### 🚀 **Happy Coding!**

