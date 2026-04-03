# Chyra

A minimal, privacy-focused realtime chat app built with modern web technologies.

No accounts. No tracking. Just join a room and start talking.

---

## 🚀 Features

* ⚡ Realtime messaging using WebSockets
* 🔐 Room-based access (room name acts as password)
* 🧠 Name stored locally (no signup/login)
* 💬 Message history per room
* 🎨 Clean UI with React + SCSS
* 🧩 Smart message rendering using pretext

---

## 🧠 How It Works

1. Enter your name (stored in browser)
2. Enter a room name
3. Anyone with the same room name joins the same chat
4. Messages sync in realtime

If a name is already taken in a room:
→ It is automatically modified (e.g. `Alex → Alex_1`)

---

## 🏗️ Tech Stack

### Frontend

* React (Vite)
* SCSS
* Socket.IO client
* pretext

### Backend

* Node.js
* Express
* Socket.IO

### Database

* SQLite

---

## 📁 Project Structure

```
frontend/   → React app (UI + client logic)
backend/    → Socket server + database
```

---

## ⚙️ Setup

### 1. Clone repo

```
git clone <your-repo-url>
cd chyra
```

---

### 2. Frontend

```
cd frontend
npm install
npm run dev
```

---

### 3. Backend

```
cd backend
npm install
node server.js
```

---

## 🧪 Current Status

Core system in development:

* [x] Project setup
* [ ] Realtime messaging
* [ ] Room system
* [ ] Message persistence

---

## ⚠️ Notes

* This is a privacy-first app, but not encrypted (yet)
* Anyone with a room name can join
* No user authentication is implemented

---

## 📌 Future Plans

* Timestamps
* Typing indicator
* Encryption layer
* PWA support

---

## 📄 License

MIT
