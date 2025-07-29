#  Quick Chat - Real Time Full Stack Chat Application

A real-time chat application built with the MERN Stack (MongoDB, Express.js, React.js, Node.js) and Socket.IO for instant messaging functionality.

##  Features

- Real-time one-to-one chat using WebSockets (Socket.IO)
- User registration and login with JWT authentication
- Online/offline user status
- Chat history saved in MongoDB
- Responsive UI with Tailwind CSS

##  Tech Stack

- **Frontend**: React (Vite), Axios, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Real-Time**: Socket.IO
- **Database**: MongoDB + Mongoose
- **Authentication**: JSON Web Token (JWT), bcrypt

---

## 📁 Project Structure

```
/client              # React (Vite) frontend
/server              # Node.js backend
/gitignore

```

---

##  Setup 

### 1. Clone the Repository

```bash
git clone https://github.com/nehadesai2424/ChatApp_MERN_Stack.git
cd ChatApp_MERN_Stack
```

### 2. Setup Server (Backend)

```bash
cd server
npm install
```

Create a `.env` file inside `/server` with:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Start backend:

```bash
npm start
```

### 3. Setup Client (Frontend)

```bash
cd ../client
npm install
```

Start frontend:

```bash
npm run dev
```

---


##  Socket.IO Overview

- Users connect to the server via WebSocket.
- Each user is tracked with their socket ID and user ID.
- Real-time messages are emitted and received using `socket.emit()` and `socket.on()`.

---


##  Dependencies

### Backend

- express
- mongoose
- socket.io
- bcryptjs
- jsonwebtoken
- cors
- dotenv

### Frontend

- react (vite)
- axios
- socket.io-client
- react-router-dom


---




