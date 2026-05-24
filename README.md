# 📚 Exam Store — NITW Previous Year Papers Platform

![React](https://img.shields.io/badge/Frontend-React.js-blue?style=for-the-badge\&logo=react)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green?style=for-the-badge\&logo=node.js)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-darkgreen?style=for-the-badge\&logo=mongodb)
![JWT](https://img.shields.io/badge/Auth-JWT-orange?style=for-the-badge)
![REST API](https://img.shields.io/badge/API-REST-blueviolet?style=for-the-badge)

> 🚀 A scalable full-stack academic resource platform enabling NIT Warangal students to efficiently search, filter, and access previous year examination papers.

---

# 🌟 Features

* 🔐 JWT-based Authentication & Authorization
* 📄 Search & Download Previous Year Papers
* 🔍 Dynamic Filtering (Semester, Subject, Faculty)
* ⚡ REST API Integration
* 📱 Responsive User Interface
* 🗂️ Organized Academic Resource Management
* 🚀 Scalable MERN Stack Architecture

---

# 🛠️ Tech Stack

## Frontend

* React.js
* HTML5
* CSS3
* Bootstrap

## Backend

* Node.js
* Express.js
* REST APIs

## Database

* MongoDB

## Authentication

* JWT (JSON Web Tokens)

---

# ⚙️ System Workflow

```text
User → React Frontend → REST API → Node.js/Express Backend → MongoDB Database
```

---

# 🚀 Installation & Setup

## Clone Repository

```bash
git clone https://github.com/RAJKUMAR8199/Exam-Store.git
```

## Navigate to Project

```bash
cd Exam-Store
```

## Install Dependencies

### Frontend

```bash
cd client
npm install
```

### Backend

```bash
cd server
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file inside the server directory.

```env
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PORT=5000
```

---

# 🔌 API Endpoints

```bash
POST /api/auth/login
GET /api/papers
GET /api/papers/filter
```

---

# 📂 Folder Structure

```bash
Exam-Store/
│
├── client/
│   ├── components/
│   ├── pages/
│   ├── services/
│
├── server/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│
├── package.json
├── README.md
```

---

# 📈 Future Improvements

* AI-powered paper recommendations
* OCR-based paper indexing
* Admin upload dashboard
* Full-text search
* Mobile application support

---

# 🌐 Deployment

Frontend:

* Vercel / Netlify

Backend:

* Render / Railway

Database:

* MongoDB Atlas

---

# 👨‍💻 Author

### Sattineni Raj Kumar

* GitHub: https://github.com/RAJKUMAR8199
* LinkedIn: Add Your LinkedIn Here
* Portfolio: Add Portfolio Link Here

