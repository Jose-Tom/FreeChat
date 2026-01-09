# FreeChat 🔐💬

FreeChat is a **1-to-1 end-to-end encrypted web chat application** built as a learning project to deeply understand **WebSockets, real-time messaging, Redis Pub/Sub, and client-side encryption**.

This project is intentionally built as a **monolith** using **Python** for the backend and **HTML/CSS/JavaScript** for the frontend, with a strong focus on **system design, tradeoffs, and failure handling**.

> ⚠️ This is **not a production-ready secure messaging app**.  
> Cryptography and security choices are simplified and made strictly for learning purposes.

---

## 🎯 Why FreeChat?

I built FreeChat to:
- Implement **WebSockets & real-time systems** is a real world use case.
- Learn **Python backend development** coming from a Go background
- Use **Redis for real infrastructure**, not just caching
- Understand **end-to-end encryption** practically
- Train myself to confidently jump into **unfamiliar technologies**
---

## 🏗 Architecture Overview

### High-Level Flow

Browser
├─ HTTP (Auth, User Profiles)
├─ WebSocket (Real-time Messaging)
└─ Client-side Encryption

FastAPI (Monolith)
├─ REST APIs
├─ WebSocket Gateway
├─ Redis (Pub/Sub, Presence)
└─ PostgreSQL (Encrypted Data Storage)


---

## 🧩 Tech Stack

### Backend
- **Python**
- **FastAPI**
- **WebSockets**
- **PostgreSQL**
- **Redis**

### Frontend
- **HTML / CSS / JavaScript**
- **React** (minimal usage)
- Built with **Cursor (AI-assisted development)**

### Security / Crypto
- Client-side encryption
- Public/private key pairs
- Encrypted message payloads only stored on server



