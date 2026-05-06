# SyncPad

Real-time collaborative code editor using CRDTs.

---

## 🚀 Overview

syncpad is a real-time collaborative code editor that allows multiple users to edit the same document simultaneously.

It uses **React + Monaco Editor + Yjs (CRDT) + Socket.IO** to provide conflict-free synchronization between clients.

---

## 🧠 Core Flow

```text id="flow3"
Monaco Editor → Yjs (CRDT) → Socket.IO → Synced Clients
```

---

## 🏗️ Architecture

```text id="arch4"
React Client (Monaco Editor)
        │
        ▼
Socket.IO Connection
        │
        ▼
Backend Server (Node.js / Express)
        │
        ▼
Yjs Document Sync (CRDT)
        │
        ▼
All Connected Clients
```

---

## 🧰 Tech Stack

### Frontend

* React
* Monaco Editor
* Yjs (CRDT)
* Socket.IO Client

### Backend

* Node.js
* Express
* Socket.IO

---

## ✨ Features

* Real-time collaborative editing
* Multiple users editing same document
* Live synchronization via WebSockets
* Conflict-free merging using CRDT
* Room-based collaboration

---

## ☁️ Deployment (Planned)

* 🐳 Docker setup for frontend and backend
* ☁️ AWS deployment (EC2 / ECS)
* ⚡ WebSocket support via Socket.IO in production

---

## 📌 Project Status

🚧 In development — core real-time collaboration system is being built.

---

## 👨‍💻 Author

Amitava Biswas
