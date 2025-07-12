# ⚡ langgraph-parallel-execution

_Run Multiple AI Tasks in Parallel Using LangGraph_

[![last commit](https://img.shields.io/github/last-commit/yourusername/langgraph-parallel-execution?style=flat-square)](https://github.com/yourusername/langgraph-parallel-execution)
[![License](https://img.shields.io/github/license/yourusername/langgraph-parallel-execution?style=flat-square)](https://github.com/yourusername/langgraph-parallel-execution/blob/main/LICENSE)
[![Python](https://img.shields.io/badge/python-100%25-blue?style=flat-square)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/langchain-✓-orange?style=flat-square)](https://www.langchain.com/)
[![LangGraph](https://img.shields.io/badge/langgraph-✓-purple?style=flat-square)](https://github.com/langchain-ai/langgraph)
[![uv](https://img.shields.io/badge/uv-pkg-blueviolet?style=flat-square)](https://github.com/astral-sh/uv)

---

## 🚀 Overview

**`langgraph-parallel-execution`** showcases how to run multiple tasks **simultaneously** within a single LangGraph workflow.  
Rather than using manual if-else logic or sequential processing, this project uses **parallel edges** to execute steps like content generation, quiz generation, and summarization all at once.

---

### ⚡ Why Parallel Execution?

- 🧵 Run independent tasks at the same time  
- 🕒 Reduce latency and improve performance  
- 🔧 Simplify complex workflows with modular nodes  
- 🔁 Replace sequential if-else logic with graph-based execution

---

## 📂 Project Structure

```bash
.
├── main.py              # LangGraph with parallel edges
├── .env                 # Environment variables (e.g., GROQ_API_KEY)
├── pyproject.toml       # Project metadata and dependencies
├── uv.lock              # Lock file (if using uv)
└── README.md            # This file

```

---

## ⚙️ Getting Started

1. Clone the repository

```bash
git clone https://github.com/yourusername/langgraph-parallel-execution.git
cd langgraph-parallel-execution
```

2. Create a virtual environment and activate it

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
```

3.Install dependencies (with uv or pip)

```bash
uv pip install -r requirements.txt
# OR
uv venv && uv pip install -e .
```

4.Add your Groq API key to a .env file

```bash
GROQ_API_KEY=your_groq_api_key_here
```

---

## 📦 Dependencies

```bash
langgraph
langchain
langchain-groq
grandalf
python-dotenv
langgraph-cli
```

---

## 📺 Video Tutorial

Watch the full walkthrough on YouTube:
🔗 https://youtu.be/xxqHImEaF1A

---

## 📜 License

This project is licensed under the MIT License.
Feel free to use, modify, and share it.
