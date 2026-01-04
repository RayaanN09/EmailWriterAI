# EmailWriterAI 📧🤖

**EmailWriterAI** is a full-stack AI-powered email generation application that helps users draft high-quality emails using natural language prompts. It combines an intelligent backend that generates email content with a user-friendly frontend UI for crafting and editing messages.

Whether you need to write professional emails, follow-ups, or casual messages, EmailWriterAI uses modern AI techniques to generate relevant and coherent text based on your input.

---

## 🔍 Features

- 🧠 AI-powered email generation  
- ✏️ Simple and intuitive UI for drafting emails  
- 🔌 Clean backend API that processes prompts and returns generated text  
- ⚡️ Fast development setup with Java backend and React frontend  
- 📦 Designed for easy extension and improvement

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React |
| Backend | Java (Spring Boot / custom backend) |
| AI | Language model (GPT/Prompt-based generator) |
| Communication | REST APIs |
| Build | Maven (backend), NPM/Yarn (frontend) |

---

## ⚙️ How It Works

1. **Frontend (React)** — Provides a form where users can enter a description or context for the email they want generated.  
2. **Backend (Java)** — Accepts prompt requests from the frontend and uses AI (or connected AI API) to generate email content.  
3. **AI Generation** — The backend processes the prompt and returns a generated email draft.  
4. **Response Rendering** — Frontend displays the generated content for editing or copying.

This architecture keeps UI and backend logic cleanly separated, making it easier to maintain and customize.

---

## 🚀 Running the Project Locally

EmailWriterAI is a full-stack application with a **Java backend** and a **React frontend**. Follow the steps below to run both parts locally.

---

### 🔧 Prerequisites

Make sure you have the following installed:

- **Java 17+**
- **Node.js (v18+)**
- **npm**
- **Maven** (optional — Maven Wrapper is included)

---

## ▶️ Backend Setup (Spring Boot)

1. Navigate to the backend directory:
   ```bash
   cd email-writer-sb
2. Run the backend using Maven Wrapper or Windows:
    ```bash
   ./mvnw spring-boot:run
   ./mvnw.cmd spring-boot:run
4. The backend will start on:
   ```bash
   http://localhost:8080
--- 

## ▶️ Frontend Setup (React)
1. Open a new terminal window and navigate to the frontend directory:
   ```bash
   cd email-writer-react
2. Install dependencies and start the react development server:
    ```bash
   npm install
   npm run dev
4. The frontend will run at:
   ```bash
   http://localhost:5173
---
