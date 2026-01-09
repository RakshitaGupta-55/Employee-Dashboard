# Employee Management Dashboard

The Employee Management Dashboard is a modern, responsive web application built using **React, TypeScript, and Vite**. This project demonstrates real-world frontend development practices using a scalable, component-based architecture and clean user interface design.

---

## 📌 Project Overview

This application includes a mock authentication system and a protected dashboard where users can manage employee records efficiently. It supports full **CRUD (Create, Read, Update, Delete)** operations, search, combined filtering, image upload with preview, and print functionality.

All employee data is stored using **browser localStorage**, which acts as a mock API, allowing data persistence without requiring a backend server.

---

## ✨ Key Features

- Mock authentication (Login / Logout)
- Protected dashboard after login
- Add, edit, and delete employee records
- Reusable employee form for add and edit
- Profile image upload with live preview
- Search employees by name
- Combined filtering by gender and active/inactive status
- Print employee list using browser print
- Data persistence using localStorage
- Clean and responsive UI using Bootstrap

---

## 🛠 Tech Stack

- React
- TypeScript
- Vite
- Bootstrap
- LocalStorage

---

## 📂 Folder Structure
src/
├─ components/
│ ├─ Login.tsx
│ ├─ Dashboard.tsx
│ ├─ EmployeeForm.tsx
│ └─ EmployeeTable.tsx
├─ utils/
│ ├─ auth.ts
│ └─ storage.ts
├─ App.tsx
└─ main.tsx


---

## ▶️ How to Run the Project Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/react-employee-dashboard.git

2️⃣ Navigate to the project directory
cd react-employee-dashboard

3️⃣ Install dependencies
npm install

4️⃣ Start the development server
npm run dev

5️⃣ Open in browser
http://localhost:5173

📝 Notes & Assumptions

Authentication is mocked for demonstration purposes

No backend server is used

localStorage is used as a mock database

node_modules is excluded from the repository using .gitignore

Dependencies can be installed using npm install

🎯 Purpose of the Project

This project was developed as part of a React.js to demonstrate practical knowledge of:

Component-based architecture

State management using React hooks

TypeScript integration in React projects

Reusable components and clean code practices

Real-world dashboard features commonly used in enterprise applications

👤 Author

Rakshita Gupta

🏆 License

This project is open-source and available under the MIT License.
