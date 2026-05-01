# 🚀 AI Code Review Tool

> An AI-powered platform that reviews code instantly and provides intelligent suggestions to improve quality, performance, readability, and best practices.

---

## 🌟 Overview

AI Code Review Tool is a full-stack web application that allows developers to paste code into an editor and receive instant AI-generated feedback.

This project helps developers:

- Detect coding mistakes
- Improve logic and efficiency
- Learn best coding practices
- Optimize readability and maintainability

---

## ✨ Features

- 🧠 AI-powered code review
- 💻 Interactive code editor
- 🎨 Clean and modern UI
- ⚡ Fast backend API response
- 📄 Markdown formatted AI feedback
- 🔍 Syntax highlighting support
- 🌐 Full-stack architecture

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Axios
- PrismJS
- React Markdown
- Highlight.js

### Backend
- Node.js
- Express.js
- REST API
- CORS

### AI Integration
- Groq API / LLM Model

---

## 📁 Project Structure

```bash
AiCodeReview/
│
├── BackEnd/
│   ├── src/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── services/
│   │   └── app.js
│   ├── server.js
│   └── package.json
│
├── Frontend/
│   ├── src/
│   │   ├── assets/
│   │   ├── App.jsx
│   │   ├── App.css
│   │   └── main.jsx
│   ├── public/
│   └── package.json
│
└── README.md

⚙️ Installation
Clone Repository
git clone https://github.com/yourusername/AiCodeReview.git
cd AiCodeReview
Backend Setup
cd BackEnd
npm install

Create .env

GROQ_API_KEY=your_api_key

Run Backend

npm start

Backend URL:

http://localhost:3000
Frontend Setup
cd Frontend
npm install
npm run dev

Frontend URL:

http://localhost:5173
🔗 API Endpoint
Review Code
POST /ai/get-review
Request Body
{
  "code": "your code here"
}
🚀 Deployment
Frontend
Vercel
Backend
Render
Live Backend
https://aicodereview-5adw.onrender.com
📌 How It Works
User Writes Code
        ↓
Frontend Sends Request
        ↓
Backend API Receives Code
        ↓
AI Processes Code
        ↓
Review Generated
        ↓
Feedback Displayed
🔒 Environment Variables

Backend .env

GROQ_API_KEY=your_api_key
🧠 Future Improvements
Multi-language support
Code history tracking
Authentication system
Export review report
Team collaboration
AI scoring system
👩‍💻 Author

Tiya Rajput

⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork the project
📢 Share with developers
💡 Code Smarter • Review Faster • Build Better
