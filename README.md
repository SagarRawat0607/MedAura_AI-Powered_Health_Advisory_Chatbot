# 🩺 AI-Powered Health Advisory Chatbot

An AI-powered web-based health advisory chatbot that provides **general health precautions and commonly known over-the-counter (OTC) medicine suggestions** based on user-reported symptoms.  
The project is designed for **educational and demonstration purposes** and does **not replace professional medical advice**.

---

## 🚀 Features

- 💬 Interactive real-time chat interface
- 🧠 AI-powered symptom-based health guidance
- 🧾 Structured and safe JSON-based AI responses
- ⚠️ Medical safety constraints (no diagnosis, no dosage, no prescriptions)
- 🌐 Full-stack implementation (Frontend + Backend)
- 🔒 Environment-based API key management

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- Vanilla JavaScript

### Backend
- Node.js
- Native HTTP server
- OpenRouter API (LLM integration)

### AI Integration
- OpenRouter-compatible LLM (e.g., Mistral)
- Prompt-constrained responses for medical safety

---

## 📁 Project Structure

MedAI/
│
├── frontend/
│ ├── landing.html
│ ├── mediBot.html
│ ├── css/
│ ├── script/
│ └── utils/
│
├── backend/
│ ├── server.js
│ ├── chatgpt.js
│ └── .env
│
└── README.md

## ⚙️ How It Works

1. User enters symptoms through the chat interface
2. Frontend sends the message to the backend via a POST API
3. Backend forwards the request to the AI model using OpenRouter
4. AI responds in a **strict JSON format**
5. Frontend formats and displays precautions, medicine names, and warnings


🧠 Safety & Design Principles

❌ No disease diagnosis

❌ No medicine dosage or prescriptions

❌ No emergency medical decisions

✅ General precautions only

✅ OTC medicine names only

✅ Doctor consultation warnings for persistent or severe symptoms



🧪 Setup Instructions

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

npm install

OPENROUTER_API_KEY=your_api_key_here

node server.js

http://localhost:5001

Open landing.html or mediBot.html in your browser.



📌 Example Use Cases

General symptom guidance (fever, cough, headache, stomach discomfort)

Lifestyle and wellness suggestions

Educational demonstration of AI + healthcare systems
