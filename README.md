
# 📝 Slack Clone 🚀

A **full-stack Slack clone** built with modern technologies like **React**, **Node.js**, **Docker**, and **MongoDB**.  
This project replicates the core chat features of Slack, including real-time messaging, room management, and authentication.

---

## ✨ Features

✅ User authentication (register & login)  
✅ Create and join chat rooms  
✅ Real-time chat messaging  
✅ Modern responsive UI with React  
✅ Backend API with Node.js & Express  
✅ MongoDB database  
✅ Dockerized frontend & backend  
✅ Easy local development with Docker Compose

---

## 📦 Project Structure

```
slack_clone/
├── backend/             # Node.js backend
│   ├── Dockerfile
│   ├── package.json
│   └── server.js
├── frontend/            # React frontend
│   ├── Dockerfile
│   ├── src/
│   │   ├── App.jsx
│   │   ├── Chat.jsx
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   ├── RoomList.jsx
│   │   ├── UserContext.jsx
│   │   └── assets/
│   │       └── react.svg
│   ├── public/
│   │   └── vite.svg
│   ├── package.json
│   └── vite.config.js
├── docker-compose.yml   # Docker Compose config
└── README.md
```

---

## 🛠️ Getting Started

### Prerequisites
- Docker & Docker Compose
- Git

### Clone the repo
```bash
git clone https://github.com/Viveksuryawanshi9405/Slack_Clone.git
cd Slack_Clone
```

### Start the app
```bash
docker-compose up --build
```

Open your browser at: `http://localhost:3000`

---

## 🐳 Docker Overview

- `frontend` → Runs React app
- `backend` → Node.js/Express API
- `mongo` → MongoDB database

Everything is containerized and orchestrated with Docker Compose.

---

## 📸 Screenshots

<img width="1920" height="969" alt="Screenshot 2025-07-14 162748" src="https://github.com/user-attachments/assets/38ac7d7b-0b20-4fec-8cde-51825b6d19a3" />


---

## 🙏 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to check the [issues page](https://github.com/Viveksuryawanshi9405/Slack_Clone/issues).

---

## ✍️ Author

Made with ❤️ by **Vivek Suryawanshi**  
[GitHub](https://github.com/Viveksuryawanshi9405)
