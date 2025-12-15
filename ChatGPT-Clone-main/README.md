# 🤖 ChatGPT Clone – Full‑Stack AI Chat Application

A modern **full‑stack ChatGPT‑like web application** that allows users to chat with an AI in real time. The project replicates core ChatGPT features including authentication, persistent conversations, markdown rendering, and a sleek responsive UI. AI responses are powered by **Google Gemini (GenAI)**.

---

## ✨ Highlights

* 🔐 **Secure Authentication** (Signup / Login / Logout)
* 🧠 **AI‑Powered Conversations** using Google Gemini API
* 💬 **Persistent Chat History** stored in MongoDB
* 📱 **Fully Responsive UI** with collapsible sidebar
* 🌙 **Dark Mode Modern Design** using Tailwind CSS
* 📝 **Markdown & Code Rendering** with syntax highlighting
* 🚀 **Production‑Ready Deployment** (Render + Vercel)

---

## 🚀 Features

### 🔑 Authentication

* JWT‑based authentication
* Encrypted passwords using bcrypt
* Session handling with cookies

### 🤖 AI Chat

* Real‑time chat with Gemini AI
* Markdown support (tables, lists, code blocks)
* Syntax highlighting for programming answers

### 🎨 User Interface

* Clean and intuitive chat layout
* Dark‑themed UI inspired by ChatGPT
* Sidebar for navigation and chat history
* Mobile‑friendly design

### 💾 Data Persistence

* Stores user details securely
* Saves prompts and AI responses
* Retrieves previous chats on login

---

## 🛠️ Tech Stack

### Backend

* **Node.js** – Server runtime
* **Express.js** – REST API framework
* **MongoDB** – Database for users & chats
* **Mongoose** – MongoDB ODM
* **JWT (jsonwebtoken)** – Authentication
* **bcryptjs** – Password hashing
* **Google Gemini API** – AI responses
* **Cookie‑Parser** – Cookie handling
* **CORS** – Cross‑origin support

### Frontend

* **React** – UI library
* **Vite** – Build & dev server
* **Tailwind CSS** – Styling
* **React Router DOM** – Routing
* **Axios** – API communication
* **Lucide React** – Icons
* **React Markdown** – Markdown rendering
* **React Syntax Highlighter** – Code blocks
* **Remark GFM** – GitHub‑flavored markdown

---

## 📂 Project Structure

```bash
chat-gpt-clone/
├── backend/
│   ├── config.js
│   ├── index.js
│   ├── controller/
│   │   ├── user.controller.js
│   │   └── promt.controller.js
│   ├── middleware/
│   │   └── promt.middleware.js
│   ├── model/
│   │   ├── user.model.js
│   │   └── promt.model.js
│   ├── routes/
│   │   ├── user.route.js
│   │   └── promt.route.js
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── tailwind.config.js
│   ├── vite.config.js
│   └── package.json
├── README.md
└── TODO.md
```

---

## ⚙️ Prerequisites

Ensure you have the following installed:

* Node.js **v18+**
* MongoDB (Local or Atlas)
* Google Gemini API Key (Google AI Studio)

---

## 🧪 Environment Variables

Create a `.env` file in the **backend** directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
```

---

## ▶️ Running the Project Locally

### Backend Setup

```bash
cd backend
npm install
npm start
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---


## 📌 Usage Guide

1. **Signup / Login** to create an account
2. Start chatting with the AI
3. View previous chats from the sidebar
4. Logout securely when finished

---

## 🔮 Future Enhancements

* Streaming AI responses
* Chat titles & search
* Multiple AI model support
* Voice input/output
* User profile management

---

## 👨‍💻 Author

Developed by **Disha Gupta**
B.Tech | Full‑Stack Developer | MERN & AI Enthusiast

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

Happy Coding 🚀
