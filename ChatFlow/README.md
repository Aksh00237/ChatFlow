# ChatFlow

ChatFlow ek real-time chat application hai jo MERN stack, Socket.io aur JWT authentication ka use karke banaya gaya hai.  
Iska goal hai fast, secure aur clean UI ke saath one-to-one messaging provide karna.

---

## 🚀 Features

- 🔐 **Secure Authentication**
  - Sign up / Login with encrypted passwords (bcrypt)
  - JWT based auth with `httpOnly` cookies for protected APIs

- 💬 **Real-time One-to-One Chat**
  - Socket.io ke through instant message delivery
  - Auto-refresh without page reload

- 🟢 **Online Users Status**
  - Logged-in users ki real-time online/offline list
  - New messages ke liye instant updates

- 📱 **Responsive UI**
  - TailwindCSS + DaisyUI se mobile, tablet aur desktop friendly layout
  - Clean and minimal chat interface

- 🧩 **Modular Code Structure**
  - Separate **backend** (API + WebSocket server) aur **frontend** (React client)
  - Reusable components and clear folder structure

---

## 🛠 Tech Stack

**Frontend**
- React.js
- Vite
- TailwindCSS
- DaisyUI
- Axios
- Socket.io Client

**Backend**
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.io
- JSON Web Token (JWT)
- bcrypt

---

## 📁 Folder Structure

```bash
ChatFlow/
├── backend/          # REST APIs, WebSocket server, database models
│   ├── src/
│   ├── package.json
│   └── ...
├── frontend/         # React + Vite client
│   ├── src/
│   ├── package.json
│   └── ...
├── package.json      # (optional) root config
└── README.md
