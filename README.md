# 🤖 SDLC Agentic AI Wizard

An interactive, agent-powered Streamlit app that guides you through the entire **Software Development Life Cycle (SDLC)** — from gathering requirements to deployment — using LLMs, LangGraph, Groq, and Streamlit.

---

## 🚀 Features

- ✅ AI-generated user stories from plain-text requirements
- 🧠 Human-in-the-loop (HITL) approval steps at every key milestone
- 📝 Auto-generated design documents (functional & technical)
- 💻 Modular code generation (split into files)
- 🔐 Automated security review with actionable feedback
- 🧪 Auto-generated test cases and QA simulations
- 🚀 Deployment triggered after QA approval
- 📊 Visual SDLC progress tracker with badges
- ⚡ Powered by LangGraph, LangChain, Groq LLMs, and Streamlit

---

## Workflow Overview
(workflow.png)


## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/lokesh-kummari/SDLC-agentic-ai.git
cd SDLC-agentic-ai

### 2. Set Up `.env` File

Create a `.env` file in the root directory to securely store your Groq API key.

```bash
touch .env

GROQ_API_KEY=your_groq_api_key_here

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

streamlit run app.py
