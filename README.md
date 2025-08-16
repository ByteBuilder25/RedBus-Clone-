# 🚌 RedBus Clone

A full-stack web application that replicates the core functionality of the popular RedBus platform.  
This project demonstrates how users can search for buses, view details, and manage bookings with a **React frontend** and a **Node.js/Express backend**.

---

## 🚀 Tech Stack

- **Frontend:** React.js, React Router, CSS  
- **Backend:** Node.js, Express.js, REST APIs  
- **Database:** (Add here if you used MongoDB / MySQL / etc.)  
- **Tools & Packages:** react-scripts, nodemon, axios, etc.

---

## ✨ Features

- 🔍 Search buses between source and destination  
- 📅 Select travel dates  
- 💺 Seat selection UI (if implemented)  
- 👤 User authentication (if implemented)  
- 📦 Backend API for bus listings and bookings  
- 🎨 Responsive design  

---

## 🛠️ Getting Started

### 🔹 Prerequisites
- Install [Node.js LTS (16 or 18 recommended)](https://nodejs.org/en/download)
- Git installed on your system

---

### 🔹 Clone the Repository

### 🔹 Setup Frontend
cd front-end-redbus
npm install
If you are on Node.js v17+ and get OpenSSL error, run:

 set NODE_OPTIONS=--openssl-legacy-provider && npm start   (Windows CMD)
 
 $env:NODE_OPTIONS="--openssl-legacy-provider"; npm start  (PowerShell)

npm start
Runs on http://localhost:3000

🔹 Setup Backend

Open another terminal:

cd back-end-redbus
npm install
npm start


⚠️ Windows PowerShell users: If you see
npm.ps1 cannot be loaded because running scripts is disabled,
run the project from Command Prompt (cmd.exe) instead, or fix with:

Set-ExecutionPolicy RemoteSigned -Scope CurrentUser


Backend usually runs on http://localhost:5000 (check your index.js or server.js for the port).



🤝 Contributing

Contributions are welcome!

Fork the repo

Create a new branch (feature-xyz)

Commit changes

Push and open a Pull Request
