# 💬 Realtime Chat Web App

A **web-based realtime chat application** built with the **MERN Stack** and powered by **Socket.IO** for instant messaging.  
Users can communicate in real-time, select themes, and enjoy a smooth, responsive UI.

---

Live Link - https://mern-chat-app-wka4.onrender.com/login

---

## 🚀 Features
- **Real-time Messaging** — Instant two-way communication with Socket.IO.
- **Theme Selection** — Multiple UI themes using DaisyUI for a personalized look.
- **User State Management** — Efficient global state handling with Zustand.
- **Responsive UI** — Mobile-friendly and optimized for all devices.
- **Persistent Storage** — Chat messages and user data stored in MongoDB.
- **Scalable Architecture** — Designed to handle multiple concurrent users.

---

## 🛠 Tech Stack
**Frontend**
- [React.js](https://react.dev/) — Component-based UI
- [Zustand](https://zustand-demo.pmnd.rs/) — Lightweight state management
- [DaisyUI](https://daisyui.com/) — Tailwind CSS component library for themes

**Backend**
- [Node.js](https://nodejs.org/) — JavaScript runtime
- [Express.js](https://expressjs.com/) — Web server framework
- [Socket.IO](https://socket.io/) — Real-time communication

**Database**
- [MongoDB](https://www.mongodb.com/) — NoSQL database for chat history and users

---


---

## ⚡ Installation & Setup

1️⃣ **Clone the repository**
```bash
git clone https://github.com/yourusername/realtime-chat-app.git
cd realtime-chat-app

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# .env
PORT=5000
MONGO_URI=your_mongodb_connection_string

# Start backend
cd backend
npm run dev

# Start frontend
cd ../frontend
npm start

# Future Enhancements

✅ Private one-on-one chat

✅ File/image sharing

✅ Message read receipts

✅ Authentication with JWT

