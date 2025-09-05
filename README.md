# Tracker Project

A full-stack **Expense Tracker Application** built with **Angular** (frontend) and **Node.js/Express** (backend).  
It allows users to register, log in, and manage expenses with persistent data storage.

---

## 🚀 Features

- 🔐 **User Authentication** (sign up & login)  
- 💰 **Expense Management** (create, view, and track expenses)  
- 📊 **Data Persistence** with backend models  
- 🐳 **Dockerized** for easy deployment  
- 🎨 **Responsive Angular Frontend**  

---

## 🛠 Tech Stack

- **Frontend:** Angular, TypeScript  
- **Backend:** Node.js, Express.js  
- **Database:** (add here if using MongoDB, MySQL, etc.)  
- **Containerization:** Docker  

## 🚀 Setup & Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/Tracker-project.git
cd Tracker-project

cd backend
npm install

cd ..
npm install

cd backend
node server.js

ng serve

docker build -t tracker-app .
docker run -p 4200:4200 tracker-app




