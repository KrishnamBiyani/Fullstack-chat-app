# 💬 Chatty

**Chatty** is a sleek, real-time one-on-one messaging platform featuring JWT authentication, media sharing, and a fully themeable UI. Built with React (Vite), Tailwind CSS, Express, Socket.IO, and MongoDB — designed for speed, simplicity, and style.

---

## 🚀 Features

- 🔐 Secure JWT-based authentication (Sign Up / Sign In)
- 💬 Real-time 1-on-1 private messaging with Socket.IO
- 🖼️ Media sharing (images, files)
- 🎨 32 built-in UI themes with instant switching
- ⚡ Blazing-fast frontend powered by Vite + Zustand
- 📱 Fully responsive and mobile-friendly design

---

## 🛠️ Tech Stack

- **Frontend**: React + Vite + Tailwind CSS + Zustand
- **Backend**: Node.js + Express + Socket.IO + JWT
- **Database**: MongoDB (via Mongoose)
- **Media Storage**: Cloudinary (configurable)

---

## ⚙️ Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/chatty.git
cd chatty
```

### 🔧 Backend Setup

```bash
cd backend
npm install
npm run dev
```

Create a `.env` file inside `/backend`:

```
PORT=5001
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
NODE_ENV=development
```

### 💻 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 📡 How It Works

```txt
[ User A ] ─┐
           │  🔄 Socket.IO
           ▼
      [ Express Server ] ── 💾 MongoDB
           ▲
           │  🔄 Socket.IO
[ User B ] ─┘
```

- Users authenticate with JWT
- Private WebSocket connections handle messaging
- Messages and media persist in MongoDB
- Media files are uploaded via Cloudinary

---

## ✅ Completed

- [x] JWT-based auth (Sign In / Sign Up)
- [x] Real-time one-on-one messaging
- [x] Socket.IO integration
- [x] Media upload (images, files)
- [x] 32 dynamic UI themes
- [x] Responsive UI with Tailwind CSS
- [x] Notifications
- [x] Online/offline status indicators

---

## 🔮 In Progress

- [ ] Chat history search
- [ ] Chat archiving
- [ ] Message reactions
- [ ] Block/report system

---
