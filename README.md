# React + Express + MongoDB Docker Compose App

A simple full-stack application using:

- React.js Frontend
- Express.js Backend
- MongoDB Database
- Docker & Docker Compose

This project demonstrates how to containerize a MERN-style application using Docker Compose.

---

# 🚀 Tech Stack

- React.js
- Node.js
- Express.js
- MongoDB
- Docker
- Docker Compose

---

# 📁 Project Structure

```bash
sample-app/
│
├── docker-compose.yml
│
├── client/
│   ├── Dockerfile
│   ├── package.json
│   └── src/
│
├── server/
│   ├── Dockerfile
│   ├── package.json
│   ├── server.js
│   └── .env
```

---

# ⚙️ Installation

## 1. Clone Repository

```bash
git clone https://github.com/your-username/sample-app.git
```

```bash
cd sample-app
```

---

# 🐳 Run with Docker Compose

## Build and Start Containers

```bash
docker-compose up --build
```

---

# 🌐 Application URLs

Frontend:

```bash
http://localhost:3000
```

Backend:

```bash
http://localhost:5000
```

MongoDB:

```bash
mongodb://localhost:27017
```

---

# 📦 Docker Services

## Client

- React frontend
- Runs on port `3000`

## Server

- Express backend
- Runs on port `5000`
- Connected with MongoDB

## Mongo

- MongoDB database
- Runs on port `27017`

---

# 🔧 Environment Variables

Create a `.env` file inside the `server` folder.

## server/.env

```env
PORT=5000
MONGO_URI=mongodb://mongo:27017/sampledb
```

---

# ▶️ Useful Docker Commands

## Start Containers

```bash
docker-compose up
```

## Start in Background

```bash
docker-compose up -d
```

## Stop Containers

```bash
docker-compose down
```

## Rebuild Containers

```bash
docker-compose up --build
```

## Remove Containers + Volumes

```bash
docker-compose down -v
```

## Check Running Containers

```bash
docker ps
```

---

# 📚 Learning Goals

This project helps understand:

- Docker basics
- Docker Compose
- Container networking
- MERN stack deployment
- MongoDB container setup
- Multi-container applications

---

# 🛠 Future Improvements

- Add authentication
- Add MongoDB Atlas support
- Add Nginx reverse proxy
- Add production Docker setup
- Add CI/CD pipeline

---

# 📄 License

This project is open-source and available under the MIT License.