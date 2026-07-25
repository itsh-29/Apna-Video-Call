# ◎ Orbit — Real-Time Video Collaboration Platform

<div align="center">

### Secure, Fast & Modern Video Conferencing Platform

Orbit is a full-stack real-time video collaboration platform that enables users to create and join secure video meetings, communicate instantly through chat, and manage meeting history. Built using WebRTC, Socket.IO, React, and Node.js, Orbit delivers low-latency peer-to-peer communication with a modern, responsive user experience.

**🌐 Live Demo:** https://your-live-demo-link.vercel.app/

> Experience seamless video conferencing with real-time communication powered by WebRTC and Socket.IO.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge)
![Material UI](https://img.shields.io/badge/Material_UI-007FFF?style=for-the-badge&logo=mui&logoColor=white)

</div>

---

# 📖 Overview

Orbit is a real-time video collaboration platform inspired by modern communication tools such as Google Meet and Zoom.

The application enables users to instantly create secure meeting rooms, invite participants, collaborate through video and chat, and maintain a history of previous meetings.

Built using **WebRTC** for peer-to-peer media streaming and **Socket.IO** for signalling and real-time communication, Orbit demonstrates full-stack engineering, authentication, and distributed real-time systems.

---

# ✨ Features

### 🔐 Secure Authentication

- User Registration
- Secure Login
- JWT Authentication
- Protected Routes
- Session Management

---

### 🎥 Real-Time Video Meetings

- Instant Meeting Creation
- Join Existing Meetings
- Unique Meeting IDs
- Peer-to-Peer Video Calls
- Multi-Participant Support
- High-Quality Audio & Video

---

### 🎙 Meeting Controls

- Microphone Toggle
- Camera Toggle
- Screen Sharing
- End Meeting
- Dynamic Participant Management

---

### 💬 Collaboration

- Real-Time Chat
- Meeting History
- Rejoin Previous Meetings
- Instant Notifications

---

### 🎨 Modern User Experience

- Responsive Interface
- Premium Black & Bronze Theme
- Clean Dashboard
- Fast Navigation
- Mobile-Friendly Design

---

# 🏗️ System Architecture

```
                 ┌──────────────────────────┐
                 │      React Frontend      │
                 │                          │
                 │ Dashboard • Meetings     │
                 │ Authentication • Chat    │
                 └────────────┬─────────────┘
                              │
                              ▼
                 ┌──────────────────────────┐
                 │    Express.js Backend    │
                 │                          │
                 │ JWT Authentication       │
                 │ REST APIs                │
                 │ Socket.IO Signalling     │
                 └────────────┬─────────────┘
                              │
              ┌───────────────┴───────────────┐
              ▼                               ▼
        MongoDB Atlas                  WebRTC Peer Connections
```

---

# 🚀 Core Functionalities

### 👤 Authentication

Secure JWT-based authentication system allowing users to register, log in, and access protected meeting routes.

---

### 📹 Video Communication

Real-time peer-to-peer video conferencing powered by WebRTC with Socket.IO used for signalling and connection management.

---

### 💬 Real-Time Messaging

Participants can exchange messages instantly during meetings without page refreshes.

---

### 📜 Meeting History

Stores previously joined meetings, allowing users to quickly revisit active sessions.

---

### 🌐 Responsive Experience

Designed to work seamlessly across desktop, tablet, and mobile devices.

---

# 🛠 Tech Stack

## Frontend

- React.js
- React Router
- Material UI
- Axios
- Socket.IO Client

## Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication

## Real-Time Communication

- WebRTC
- Socket.IO

## Deployment

- Vercel
- Render
- MongoDB Atlas

---

# 📂 Project Structure

```
Orbit
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── contexts/
│   │   ├── styles/
│   │   └── utils/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── app.js
│
├── package.json
└── README.md
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/itsh-29/Orbit.git
```

```bash
cd Orbit
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm start
```

---

## Backend Setup

```bash
cd backend

npm install

npm run dev
```

---

## Configure Environment Variables

Create a `.env` file inside the backend directory.

```env
PORT=8000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_secret_key
```

---

The backend runs on:

```
http://localhost:8000
```

The frontend runs on:

```
http://localhost:3000
```

---

---

# 📦 Libraries Used

### Frontend

- React
- Material UI
- Axios
- React Router
- Socket.IO Client

### Backend

- Express
- Mongoose
- JWT
- Socket.IO

### Database

- MongoDB Atlas

### Communication

- WebRTC

---

# 💡 Future Improvements

- 📅 Meeting Scheduling
- 👥 User Profiles
- 📧 Meeting Invitations
- 📁 File Sharing
- 🤖 AI Meeting Notes
- 🎥 Meeting Recording
- 🔒 End-to-End Encryption
- 🌙 Dark & Light Themes
- 📊 Meeting Analytics
- 🔔 Push Notifications

---

# 📚 Learning Outcomes

This project helped me gain practical experience with:

- WebRTC Peer-to-Peer Communication
- Socket.IO Real-Time Applications
- JWT Authentication
- React State Management
- REST API Development
- MongoDB Data Modeling
- Express Backend Development
- Responsive UI Design
- Full-Stack Deployment
- Real-Time System Design

---

# 🤝 Contributing

Contributions, suggestions, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Ishan Meduri**

- GitHub: https://github.com/itsh-29
- LinkedIn: https://www.linkedin.com/in/ishanmeduri

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
