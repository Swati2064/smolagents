# 🤖 Smolagents — Agentic AI & Generative AI

<p align="center">
  <b>Building AI Agents with Python, Smolagents, LLMs & Web Search</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Smolagents-Agentic%20AI-orange?style=for-the-badge" alt="Smolagents">
  <img src="https://img.shields.io/badge/Generative%20AI-LLM-purple?style=for-the-badge" alt="Generative AI">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" alt="Jupyter">
  <img src="https://img.shields.io/badge/GitHub-Version%20Control-black?style=for-the-badge&logo=github" alt="GitHub">
</p>

---

## 📌 About the Project

This project demonstrates the fundamentals of **Agentic AI and Generative AI** using the **Smolagents framework**.

The project explores how AI agents can use Large Language Models (LLMs), tools, Python code execution, and web search capabilities to solve tasks autonomously.

The notebooks included in this repository demonstrate practical implementations of AI agents using Python.

---

## 🚀 Project Features

* 🤖 AI Agent development using **Smolagents**
* 🧠 Large Language Model integration
* 💻 Code-based AI agents
* 🔎 Web search capabilities
* 🛠️ Tool-using AI agents
* 📓 Jupyter Notebook implementations
* 🔐 Secure API key management using `.env`
* 🌐 Generative AI workflows
* ⚡ Agentic task execution

---

## 📂 Project Structure

```text
smolagents/
│
├── 📓 ml_code_agents.ipynb
├── 📓 websearch.ipynb
├── 🔐 .gitignore
└── 📄 README.md
```

### 📓 `ml_code_agents.ipynb`

Demonstrates a **code-based AI agent** that can use an LLM and execute Python-based tasks.

Key concepts covered:

* CodeAgent
* LLM integration
* Tool usage
* Python code execution
* Agentic workflows
* Generative AI

### 🔎 `websearch.ipynb`

Demonstrates an AI agent capable of performing **web search and retrieving information**.

Key concepts covered:

* Web-search agents
* Search tools
* Agent reasoning
* Tool calling
* LLM-powered information retrieval

---

## 🧠 What is Agentic AI?

**Agentic AI** refers to AI systems that can independently perform tasks by:

```text
User Goal
    ↓
AI Agent
    ↓
Reasoning
    ↓
Tool Selection
    ↓
Tool Execution
    ↓
Result Analysis
    ↓
Final Answer
```

Unlike a traditional chatbot that only generates text, an AI agent can interact with tools and take actions to accomplish a goal.

---

## 🤖 What is Smolagents?

**Smolagents** is a lightweight framework for building AI agents.

It allows developers to create agents that can:

* Use LLMs
* Call tools
* Execute Python code
* Search the web
* Perform multi-step tasks
* Automate workflows

This makes it useful for learning and developing **Agentic AI applications**.

---

## 🛠️ Technologies Used

| Technology          | Purpose                         |
| ------------------- | ------------------------------- |
| 🐍 Python           | Programming language            |
| 🤖 Smolagents       | AI Agent framework              |
| 🧠 LLMs             | Reasoning & generation          |
| 🔎 Web Search       | Information retrieval           |
| 📓 Jupyter Notebook | Development & experimentation   |
| 🔐 dotenv           | Environment variable management |
| 🐙 Git & GitHub     | Version control                 |

---

## 🔐 API Key Security

API keys are **not stored directly in the notebooks**.

Create a `.env` file in the project directory:

```env
GOOGLE_API_KEY=your_google_api_key
HUGGINGFACE_API_KEY=your_huggingface_api_key
```

Then load the environment variables in Python:

```python
from dotenv import load_dotenv
import os

load_dotenv()

google_api_key = os.getenv("GOOGLE_API_KEY")
huggingface_api_key = os.getenv("HUGGINGFACE_API_KEY")
```

### ⚠️ Important

Never upload `.env` to GitHub.

The project includes:

```text
.env
```

in `.gitignore` to prevent API keys from being committed.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Swati2064/smolagents.git
```

### 2. Navigate to the project

```bash
cd smolagents
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install smolagents
```

For web-search functionality, install the required search/tool dependencies used in the notebook.

---

## ▶️ Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
ml_code_agents.ipynb
```

or:

```text
websearch.ipynb
```

Run the cells step by step.

---

## 📚 Concepts Learned

This project covers important concepts in modern AI development:

* Large Language Models
* Prompt Engineering
* AI Agents
* Agentic AI
* Tool Calling
* Code Agents
* Web Search Agents
* LLM APIs
* Environment Variables
* Generative AI
* Autonomous Task Execution

---

## 🎯 Learning Objectives

The main objectives of this project are to understand how to:

1. Build an AI agent using Python.
2. Connect an LLM with an agent.
3. Give tools to an AI agent.
4. Allow agents to execute code.
5. Build web-search-enabled agents.
6. Secure API keys using environment variables.
7. Understand the fundamentals of Agentic AI.

---

## 🔮 Future Improvements

Possible future enhancements include:

* 🧠 Multi-agent systems
* 🔗 RAG-based AI agents
* 📚 Vector database integration
* 🌐 More web tools
* 🛠️ Custom agent tools
* 💬 Conversational AI agents
* 📊 Agent monitoring and evaluation
* 🚀 Deployment using Streamlit or FastAPI
* 🔄 Agent workflow automation

---

## 👩‍💻 Author

**Swati Jadhav**

🎓 B.Tech — Artificial Intelligence & Data Science

---

<p align="center">
  <b>🤖 Exploring Agentic AI • Generative AI • LLMs • AI Agents</b>
</p>


