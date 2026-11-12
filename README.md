# 🚀 Atreides AI – Intelligent University Helpdesk Assistant

Atreides AI is an AI-powered university helpdesk chatbot designed to help students access university-related information through a conversational interface. It uses Natural Language Processing and Large Language Models to understand student queries and generate relevant responses.

## ✨ Features

- 🤖 **AI-Powered Chatbot:** Generates intelligent responses using the Groq API.
- 💬 **Natural Language Interaction:** Students can ask questions conversationally.
- ⚡ **Fast Backend:** Powered by Python and FastAPI.
- 🎨 **Modern User Interface:** Built using React and Vite.
- 🧠 **Intent Understanding:** Designed to identify and route student queries.
- 🔗 **API Integration:** Connects frontend and backend for real-time communication.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend development |
| Vite | Frontend development server |
| Python | Backend programming |
| FastAPI | Backend API framework |
| Groq API | AI-powered response generation |
| HTML, CSS, JavaScript | User interface |
| REST API | Frontend-backend communication |

## 📂 Project Structure

```text
Atreides-AI/
│
├── backend/
│   └── Backend source code
│
├── frontend/
│   └── React application
│
├── docs/
│   └── Project documentation
│
├── ATREIDES_SETUP.md
├── DEPLOYMENT.md
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Jatin-verma001/Chatbot-for-university-student.git
```

```bash
cd Chatbot-for-university-student
```

### 2. Backend Setup

Create a Python virtual environment:

```bash
python -m venv .venv
```

Activate it in Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Install backend dependencies using the dependency file available in your project:

```bash
pip install -r requirements.txt
```

Configure your `.env` file with your Groq API key:

```env
GROQ_API_KEY=your_groq_api_key
```

Start the backend using the correct FastAPI entry point. For example, if the application is in `backend/main.py`:

```bash
uvicorn backend.main:app --reload --port 8001
```

### 3. Frontend Setup

Open another terminal:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL displayed by Vite, usually:

```text
http://localhost:5173
```

## 🔌 API Documentation

If the backend is running on port 8001, access the FastAPI documentation at:

```text
http://localhost:8001/docs
```

## 🎯 Project Objectives

- Provide students with a centralized university helpdesk.
- Make university information easier to access.
- Reduce repetitive manual helpdesk queries.
- Improve the student experience through AI-powered assistance.
- Explore practical applications of Artificial Intelligence and NLP.

## 🔮 Future Enhancements

- University-specific knowledge base integration.
- Advanced intent classification using Machine Learning.
- Retrieval-Augmented Generation (RAG).
- Multilingual chatbot support.
- Student authentication and personalized assistance.
- Conversation history and feedback system.
- Cloud deployment and performance monitoring.

## 🔐 Security & Privacy

- Store API credentials securely using environment variables.
- Never expose API keys in frontend code or public repositories.
- Avoid collecting unnecessary personal information.
- Verify important information through official university sources.

## 👨‍💻 Developer

**Jatin Verma**

Computer Science & Engineering | Data Science

## 🔗 Project Repository

Explore the complete project here:

**[Atreides AI – Chatbot for University Students](https://github.com/Jatin-verma001/Chatbot-for-university-student)**

---

⭐ If you find this project interesting, consider giving the repository a star!
