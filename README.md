# Threads - Chat Application 🚀

![Frontend](https://img.shields.io/badge/Frontend-React-blue)
![Backend](https://img.shields.io/badge/Backend-Node.js-green)
![Database](https://img.shields.io/badge/Database-MongoDB-yellow)
![Hosting](https://img.shields.io/badge/Hosting-Vercel-blue)
![Socket.IO](https://img.shields.io/badge/RealTime-Socket.IO-lightgrey)

A **real-time chat application** with text and image messaging, online/offline status, and unseen message tracking.

---

## Features ✨

- Real-time messaging using **Socket.IO**
- Text and image message support
- Online/offline user status
- Unseen message notifications
- Responsive design
- Automatic scroll to latest message

---

## Tech Stack 🛠

**Frontend:** React, Tailwind CSS, React Router  
**Backend:** Node.js, Express.js, MongoDB, Socket.IO  
**Other Tools:** Axios, React Hot Toast  

---

## 📂 Folder Structure

```bash
chat-app/
│
├─ client/                     # React frontend
│  ├─ src/
│  │  ├─ assets/               # Images, icons
│  │  ├─ components/           # React components
│  │  ├─ pages/                # Page components
│  │  ├─ lib/                  # Utilities (e.g., formatMessageTime)
│  │  ├─ Context/              # AuthContext, ChatContext
│  │  └─ App.jsx
│  └─ package.json
│
├─ server/                     # Node.js backend
│  ├─ controllers/             # API logic
│  ├─ models/                  # Mongoose schemas
│  ├─ routes/                  # Express routes
│  ├─ middlewares/             # Auth or error handling
│  └─ package.json
│
├─ .gitignore
└─ README.md
```
---

## Installation 💻

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/driveon.git
   cd driveon

2. Install frontend dependencies:
   ```bash
    cd client
    npm install
3. Install backend dependencies:
   ```bash
   cd ../server
   npm install
4. Setup environment variables in server/.env:
   ```bash
   PORT=5000
   JWT_SECRET=
   MONGO_DB_URL="your-database-uri"
   CLOUDINARY_CLOUD_NAME='your-cloudinary-cloud-name'
   CLOUDINARY_API_KEY='your-cloudinary-api-key'
   CLOUDINARY_API_SECRET='cloudinary-api-secret'
5. Setup environment variables in client/.env:
   ```bash
   VITE_CURRENCY=Rs.
   VITE_BASE_URL=you-server-url
6. Run the application:
   ```bash
   # Backend (New Terminal)
   cd server
   npm run server
    
   # Frontend (New Terminal)
   cd client
   npm run dev

---

## 📄 Usage

- Register or log in as a user
- Select a user from the sidebar to start a chat
- Send text or image messages
- Track unseen messages and online/offline status
