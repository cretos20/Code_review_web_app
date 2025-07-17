# 🧠 AI Code Review Web App

A full-stack web application that leverages Google Gemini AI to provide intelligent, real-time code reviews. Users can input JavaScript code into a sleek editor interface, and receive feedback with suggested improvements, performance tips, and best practices — all powered by AI.

---

## 🚀 Live Demo

🌐 [Open Link](https://your-frontend-url.vercel.app)  

---

## 🛠 Tech Stack

### 🔹 Frontend
- **React.js** — Built with modern component-based UI
- **Vite** — Fast and lightweight development bundler
- **Tailwind CSS** — Utility-first styling for responsive design
- **PrismJS** — Syntax highlighting for code input
- **React Simple Code Editor** — Lightweight code editor UI
- **React Markdown + Rehype Highlight** — Renders AI output with formatted code

### 🔹 Backend
- **Node.js** — JavaScript runtime for backend logic
- **Express.js** — Lightweight framework for RESTful API
- **Google Generative AI (Gemini API)** — For generating intelligent code reviews
- **dotenv** — Secure environment variable management
- **CORS** — Cross-origin access setup for frontend communication

### 🔹 Deployment
- **Vercel** — Frontend hosting
- **Render** — Backend hosting
- **Hostinger** — Connected with custom domain

---

## 💡 Features

- ✨ **Real-Time Code Reviews** — Instantly receive detailed feedback for your code
- 🧠 **AI-Powered Suggestions** — Leverages Google Gemini AI for code analysis
- 🛠 **Developer-Friendly Editor** — Includes syntax highlighting and markdown-formatted output
- ⚙️ **Modular Backend** — Cleanly separated logic using MVC pattern
- 🌍 **Deployed with Custom Domain** — Hosted on Vercel and connected via Hostinger

---

## ⚙️ How It Works

1. User enters code into the UI (frontend).
2. On clicking "Review", the code is sent to the Express backend API.
3. The backend calls the **Google Gemini API** using `@google/generative-ai`.
4. AI returns a markdown-formatted code review with:
   - Bug detection
   - Best practice suggestions
   - Performance improvements
   - Security insights
5. The frontend renders the markdown beautifully using `react-markdown`.

---

## 🧪 Local Setup

### 1. Clone the Repo

git clone https://github.com/cretos20/Code_review_web_app.git
cd code-review-app

### 2. Setup Backend

cd backend
npm install

Create a .env file:
GOOGLE_GEMINI_KEY=your_google_api_key

node server.js

### 3. Setup Frontend

cd ../frontend
npm install
npm run dev

