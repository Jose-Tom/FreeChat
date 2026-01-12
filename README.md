# FreeChat 🔐💬

FreeChat is a **1-to-1 end-to-end encrypted web chat application** built as a learning project to deeply understand **real-time messaging, Socket.IO, Redis Pub/Sub, and client-side encryption**.

This project is intentionally built as a **monolith** using **Node.js** for the backend and **HTML/CSS/JavaScript** for the frontend, with a strong focus on **system design, tradeoffs, and failure handling**.

> ⚠️ This is **not a production-ready secure messaging app**.  
> Cryptography and security choices are simplified and made strictly for learning purposes.

---

## 🎯 Why FreeChat?

I built FreeChat to:
- Implement **real-time chat systems** using Socket.IO in a real-world use case
- Learn **Node.js backend development** with limited prior experience
- Use **Redis as real infrastructure**, not just a cache
- Understand **end-to-end encryption** from a practical perspective
- Design and reason about **stateful, event-driven systems**
- Train myself to confidently jump into **unfamiliar technologies by building**

---

## 🏗 Architecture Overview

### High-Level Flow

Browser
├─ HTTP (Auth, User Profiles)
├─ Socket.IO (Real-time Messaging)
└─ Client-side Encryption

Node.js (Express Monolith)
├─ REST APIs
├─ Socket.IO Server
├─ Redis (Pub/Sub, Presence)
└─ PostgreSQL (Encrypted Message Storage)


---

## 🧩 Tech Stack

### Backend
- **Node.js**
- **Express**
- **Socket.IO**
- **PostgreSQL**
- **Redis**

### Frontend
- **HTML / CSS / JavaScript**
- **React** (minimal usage)
- Built with **Cursor (AI-assisted development)**

### Security / Crypto
- Client-side encryption
- Public/private key pairs
- Encrypted message payloads only stored on the server
