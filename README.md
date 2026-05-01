# 🚀 AI Code Review Tool

> An AI-powered platform that reviews code instantly and provides intelligent suggestions to improve quality, performance, readability, and best practices.
## Live Link: https://ai-code-review-virid.vercel.app/
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

## 📌 How It Works
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
