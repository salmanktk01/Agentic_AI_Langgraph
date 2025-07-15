# 🤖 Agentic AI with LangGraph – Chatbot Projects

This repository contains five Jupyter Notebook-based chatbot projects built using the langGraph framework. Each project showcases a unique capability of building intelligent, tool-using, and memory-aware conversational AI agents.

---

## 📁 Projects Overview

### ✅ 1. Human-in-the-Loop Chatbot
- **Description**: A LangGraph-powered chatbot that integrates a human assistance mechanism using `interrupt()`.
- **Key Features**:
  - Human-in-the-loop tool (`human_assistance`)
  - Web search integration (Tavily)
  - Memory management with `MemorySaver`
  - Streaming responses

### ✅ 2. Tool-Calling Chatbot (React-Inspired Architecture)
- **Description**: A chatbot agent where the LLM dynamically decides when to invoke tools, inspired by React’s state-driven rendering.
- **Key Features**:
  - Modular graph with conditional routing
  - Custom tool (`my_func`) and Tavily integration
  - Looped flow between LLM and tools

### ✅ 3. Basic LLM Chatbot
- **Description**: A minimal LangGraph chatbot using only an LLM for simple interactions.
- **Key Features**:
  - No memory or tools
  - One-turn or multi-turn response generation
  - Foundation for testing or experimentation

### ✅ 4. Memory-Enhanced Chatbot
- **Description**: A chatbot that uses LangGraph and `MemorySaver` to maintain conversation state over multiple turns.
- **Key Features**:
  - Persistent memory across steps
  - Prepares the chatbot for long-form or contextual interactions

### ✅ 5. Multi-Tool Chatbot
- **Description**: A chatbot capable of dynamically using multiple tools during a single conversation loop.
- **Key Features**:
  - Integrates multiple tools like `tavily_search`, `human_assistance`, `my_func`
  - LangGraph flow control for sequential or parallel tool usage
  - LLM-driven decision-making across tools

---
📦 Dependencies
Python 3.10+

- langgraph

- langchain

- tavily (for search)

- Jupyter Notebook

- LLM backend (ChatGroq)


---

## ✨ Features

- ✅ Modular agent design using LangGraph
- 🔁 Looping logic between LLM and tools
- 🧠 Built-in memory with `MemorySaver` for contextual understanding
- 🔧 Tool integration: web search (Tavily), math tool (`my_func`), and human feedback (`interrupt`)
- 📤 Streaming support for real-time LLM outputs
- 🔍 Conditional tool execution based on message content
- 📦 Jupyter Notebook format for interactive development

---
