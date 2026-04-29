# 📚 Library Management System

A full-stack **Library Management System** designed to efficiently manage books, users, and library operations.
This system provides a clean and intuitive interface for managing book records, issuing and returning books, and tracking availability in real time.

---

## 👨‍💻 Team Members

* **CHITIPROLU DINESH** – `AP24110011504`
* **CHARAN KOYA** – `AP24110011508`
* **RANJITH VIJAY** – `AP24110011505`
* **SAI CHATURVEDI** – `AP24110011463`

---

## 🚀 Features

* 📖 Add, update, delete, and view books
* 👤 Manage library users/members
* 🔍 Search books by title, author, or category
* 📚 Issue and return books with record tracking
* 📅 Due date and availability management
* 🔐 Authentication system using JWT
* 🛠️ Admin dashboard for centralized control
* 🌐 Full-stack architecture with REST APIs

---

## 🛠️ Tech Stack

### 💻 Frontend (Client)

* React.js (Vite)
* JavaScript (ES6+)
* HTML5 & CSS3
* Axios
* Context API (Auth Management)

### ⚙️ Backend (Server)

* Node.js
* Express.js
* JWT Authentication
* REST API Architecture

### 🗄️ Database

* MongoDB with Mongoose

---

## 📂 Project Structure

```
library-management-system/
│
├── client/                         # Frontend (React + Vite)
│   ├── src/
│   │   ├── api/                    # API calls (Axios)
│   │   ├── components/             # Reusable UI components
│   │   ├── context/                # Authentication context
│   │   ├── hooks/                  # Custom hooks
│   │   ├── layouts/                # Layout components
│   │   ├── pages/                  # Application pages
│   │   │   ├── admin/              # Admin pages
│   │   │   ├── DashboardPage.jsx
│   │   │   ├── LoginPage.jsx
│   │   │   ├── RegisterPage.jsx
│   │   │   └── ...
│   │   ├── styles/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── index.html
│   └── package.json
│
├── server/                         # Backend (Node + Express)
│   ├── src/
│   │   ├── config/                # DB & app configuration
│   │   ├── controllers/           # Business logic
│   │   ├── middleware/            # Auth middleware
│   │   ├── models/                # Mongoose models
│   │   ├── routes/                # API routes
│   │   ├── seed/                  # Seed data
│   │   ├── utils/                 # Utility functions
│   │   ├── app.js
│   │   └── server.js
│   ├── .env
│   └── package.json
│
├── docker-compose.yml
├── .gitignore
└── README.md
```

---

## 📸 Screenshots

Below are some snapshots of the system showcasing key functionalities and user interface:

### 🔹 Dashboard & Overview

![Dashboard](https://github.com/user-attachments/assets/388b41ae-ccc7-41de-85a0-ffa176f79512)

### 🔹 Book Management

![Books](https://github.com/user-attachments/assets/ea018149-fe88-40a4-9076-855b5ed06fc5)

### 🔹 Issue & Return System

![Issue Return](https://github.com/user-attachments/assets/dc11ade3-49a7-498b-a787-5cacc1ffd016)

### 🔹 User Management

![Users](https://github.com/user-attachments/assets/7cbe9ff5-400f-4109-9388-d181b51178e5)

### 🔹 Search & Filters

![Search](https://github.com/user-attachments/assets/f5e9d7de-986e-4345-a5e5-a390f5fc0240)

### 🔹 Additional UI View

![UI](https://github.com/user-attachments/assets/279b1d95-60e5-4b42-b0d6-2baac2cd8161)

---

## 🎥 Demo Videos

### 📽️ Project Walkthrough (UI & Features)

https://github.com/user-attachments/assets/bf63ccb3-86ef-496d-bea8-50bb5696afd4

### 💻 Code Explanation & Architecture

https://github.com/user-attachments/assets/62041058-38ec-4178-a1a9-01cc8dbf9a5f

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/library-management-system.git
cd library-management-system
```

### 2️⃣ Backend Setup

```
cd server
npm install
npm run dev
```

### 3️⃣ Frontend Setup

```
cd client
npm install
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file inside the **server** folder:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

---

## 🎯 Future Enhancements

* 🔐 Role-based access control (Admin/User)
* 📊 Advanced analytics dashboard
* 📱 Fully responsive UI
* 📧 Email notifications for due dates
* ☁️ Cloud deployment (AWS / Render / Vercel)

---

## 📄 License

This project is developed for academic and learning purposes.

---

## ⭐ Acknowledgement

This project was developed to gain practical experience in **full-stack development**, API design, and real-world application architecture.
