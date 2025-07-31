# CodeGuardian 🛡️

CodeGuardian is an **AI-powered code review tool** that uses **Google Gemini** to provide intelligent, real-time feedback on your code.  
It helps developers improve **code quality, performance, readability, and maintainability** directly from a simple frontend editor.

---

## 🚀 Features
- ✨ AI-driven code reviews using **Google Gemini 2.5 Flash**
- 🖥️ Interactive code editor (React + Vite + `react-simple-code-editor`)
- 📑 Markdown-based review results with syntax highlighting
- 🌐 Express.js backend to handle Gemini API requests
- 🔐 Secure API key management using `.env`

---

## 🛠️ Tech Stack
- **Frontend**: React (Vite), Prism.js, React-Markdown, Highlight.js
- **Backend**: Node.js, Express.js, CORS
- **AI**: Google Gemini API (`@google/genai`)
- **Other Tools**: Axios, Dotenv, Nodemon

---

## 📂 Project Structure
CodeGuardian/

│── BackEnd/ # Node.js + Express API

│ ├── src/

│ │ ├── controllers/

│ │ ├── routes/

│ │ └── services/

│ ├── server.js

│ └── package.json

│

│── Frontend/ # React + Vite frontend

│ ├── src/

│ │ └── App.jsx

│ ├── package.json

│ └── index.html

│

└── .gitignore # ignores node_modules + .env



---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/CodeGuardian.git
cd CodeGuardian

### 2️⃣ Backend Setup
    cd BackEnd
    npm install

    Create a .env file inside BackEnd/:
    GOOGLE_GEMINI_KEY=your_api_key_here

    Run the backend:
    npx nodemon

    Server will start at http://localhost:3000

### 3️⃣ Frontend Setup

    cd ../Frontend
    npm install
    npm run dev

    Frontend runs at http://localhost:5173
