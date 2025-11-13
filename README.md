# 💬 Chat App (No Images)

A full-stack real-time chat application built with the MERN stack and Socket.IO.
This version focuses on **text-only messaging**, keeping the architecture simple and clean.

🎥 **Demo Video:**  
https://vimeo.com/1136501312?fl=ip&fe=ec

---

## 🚀 Features

- 🔐 **Authentication & Authorization** – JWT-based login + protected routes
- 💭 **Real-time Messaging** – Instant 1:1 chat using Socket.IO
- 🟢 **Live Online Status** – See which users are online
- 📬 **Message History** – Chats stored in MongoDB
- 🔒 **Secure Password Hashing**
- 🧹 **Text-only chat** – No image handling for simplicity

---

## 🧱 Tech Stack

### Backend
- Node.js
- Express
- MongoDB + Mongoose
- Socket.IO
- JWT Auth

### Frontend
- React
- Socket.IO Client
- Tailwind CSS (or preferred styling)
- Custom hooks & context

---

## 📁 Project Structure

```
chat-app-noimg/
  backend/
    src/
    .env.example
  frontend/
    src/
  package.json
```

---

## ⚙️ Prerequisites
- Node.js (LTS)
- npm or yarn
- MongoDB (local or Atlas)

---

## 🔧 Backend Setup

```bash
cd backend
npm install
```

Create `.env`:
```env
MONGODB_URI=your_mongodb_uri
PORT=5001
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
```

Start backend:
```bash
npm run dev
```

---

## 🎨 Frontend Setup

```bash
cd frontend
npm install
```

Optional `.env`:
```env
VITE_API_URL=http://localhost:5001
```

Start frontend:
```bash
npm run dev
```

---

## ▶️ How to Run
1. Start backend: `npm run dev`
2. Start frontend: `npm run dev`
3. Open browser and chat freely.

---

## 📌 Future Improvements
- Typing indicators
- Read receipts
- Group chats
- Search messages
- Image/file upload (optional)

---

## 👤 Author
Created by **Eduard Amza** – https://github.com/edyamza
