# 🧠 AI-Agent – Intelligent Web Task Automation

An AI-powered assistant that simulates human-like web interaction using LLMs and a web UI. Built using `browser-use` and `web-ui`, this project can browse, extract, and act on webpages based on natural language prompts.

---

## 🚀 Features

* 🔍 Search and interact with webpages intelligently
* 🤖 Gemini Pro / OpenAI 
* 🧠 Task planning, history logging, and agent memory
* 🌐 Web UI interface powered by Gradio
* 🐳 Dockerized for easy deployment
* 🛡️ `.gitignore` & `.env.example` for safe configuration

---

## 🛠️ Tech Stack

| Layer         | Tech                           |
| ------------- | ------------------------------ |
| Backend       | Python, FastAPI / Flask        |
| Frontend      | Gradio                         |
| Web Control   | Playwright                     |
| AI Engine     | LangChain, Gemini, IBM WatsonX |
| Containerized | Docker + Docker Compose        |

---

## 🧪 Setup Instructions

### 🔧 Local Setup

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/ai-agent.git
cd ai-agent

# 2. Navigate into the web-ui directory
cd web-ui

# 3. Set up virtual environment
python -m venv .venv
source .venv/bin/activate    # (use .venv\Scripts\activate on Windows)

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the app
python webui.py --ip 127.0.0.1 --port 7788
```

### 📅 Access the App

Once running, open your browser and go to:

👉 **[http://127.0.0.1:7788](http://127.0.0.1:7788)**

> This is your local AI-Agent interface.

---

## 📂 Project Structure

```
ai-agent/
├── web-ui/
│   ├── src/                    # Frontend & logic
│   ├── assets/                 # Static files
│   ├── tests/                  # Tests (optional)
├── .env.example                # Environment template
├── .gitignore                  # Ignored files
├── docker-compose.yml
├── Dockerfile
├── README.md                   # This file
├── LICENSE
└── webui.py                    # App entrypoint
```

---

## ✍️ About This Project

This AI agent was built as a hands-on implementation of LLM-powered browser control. It is inspired by:

* browser-use
* web-ui

🔧 Custom features added:

* Local history tracking
* Prompt handling via Gemini
* `.env`-based configuration
* Clean modular folder structure

---



