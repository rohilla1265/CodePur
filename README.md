Markdown
# 🚀 CodePur — Interactive Coding & Online Judge Platform

**CodePur** is a full-stack competitive programming and problem-solving platform. It features an integrated code compiler (via Judge0), video solutions, submission history tracking, an admin management dashboard, and an AI Chat Assistant to help users debug and learn effectively.

---

## ✨ Features

- 👨‍💻 **Problem Solving Platform:** Browse and solve algorithmic coding problems with real-time test-case evaluation.
- ⚡ **Multi-Language Support:** Code execution supported for **C++**, **Java**, and **JavaScript**.
- ⚙️ **Judge0 Execution Engine:** Secure and scalable remote code compilation and evaluation.
- 🤖 **AI Chat Assistant:** In-platform AI assistant to guide users, explain logic, and help debug errors.
- 🎥 **Video Solutions:** Watch detailed video explanations for complex problems directly on the solution page.
- 📊 **Submission Tracker:** Track your past code submissions, verdicts (Accepted, TLE, WA), runtime, and memory.
- 🏎️ **Redis Integration:** Used for fast session/login handling, rate limiting, and execution queue processing.
- 👑 **Admin Dashboard:**
  - Create, Update, and Delete coding problems.
  - Upload/Attach video solutions.
  - Manage test cases and problem difficulty levels.

---

## 🛠️ Tech Stack

- **Frontend:** React / Next.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database & Cache:** Redis, MongoDB / PostgreSQL
- **Code Execution API:** Judge0 Engine
- **AI Integration:** gemini API / Custom LLM Chatbot

---

## 🚀 Getting Started

Follow these instructions to set up and run CodePur on your local machine.

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [Redis](https://redis.io/) server running locally or cloud URL
- [Judge0](https://judge0.com/) API keys (or local Docker instance)

---

### 📥 1. Clone the Repository

```bash
git clone [https://github.com/your-username/codepur.git](https://github.com/your-username/codepur.git)
cd codepur
⚙️ 2. Environment Setup
Create .env files in both frontend and backend root directories:

Backend .env

Code snippet
PORT=5000
DATABASE_URL=your_database_url
REDIS_URL=redis://localhost:6379
JWT_SECRET=your_jwt_secret
JUDGE0_API_KEY=your_judge0_api_key
AI_API_KEY=your_ai_chat_key
Frontend .env

Code snippet
VITE_API_BASE_URL=http://localhost:5000/api
💻 3. Running the Application
Backend Setup
Bash
cd backend
npm install
npm run start
Frontend Setup
Bash
cd frontend
npm install
npm run dev
Open http://localhost:5173 (or your local dev URL) in your browser.

🗂️ Project Architecture
Plaintext
CodePur/
├── frontend/               # User interface (React/Next.js)
│   ├── src/
│   │   ├── components/     # Code Editor, AI Chat, Problem Cards
│   │   ├── pages/          # Admin Dashboard, Problem Set, Solution Page
│   │   └── services/       # API integration
│   └── package.json
│
├── backend/                # Server & Judge0/Redis pipeline
│   ├── controllers/        # Auth, Problems, Submissions, Admin logic
│   ├── models/             # User, Problem, Submission models
│   ├── routes/             # API Endpoints
│   ├── utils/              # Redis & Judge0 helpers
│   └── package.json
└── README.md
🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📜 License
Distributed under the MIT License.


<ElicitationsGroup message="Project presentation boost karne ke options:">

  <Elicitation label="GitHub badges aur screenshots section add karein" query="CodePur README mein dynamic GitHub badges aur screenshots placeholder section add kar do."/>
  <Elicitation label="Judge0 setup guide add karein" query="README mein Judge0 local Docker setup instruction steps bhi add kar do."/>
</ElicitationsGroup>
