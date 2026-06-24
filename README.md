# 🤖 Multi-Agent AI Platform

A multi-use-case AI platform built using **LangGraph**, **LangChain**, **Groq LLMs**, **Tavily Search**, and **Streamlit**. The platform integrates multiple AI workflows into a single application, enabling conversational AI, real-time web search, and AI-powered news summarization.



[link to deployed website](https://agentic-chatbot-langraph.streamlit.app/)
---

## 🚀 Features

### 💬 AI Chatbot
- Interactive conversational AI assistant
- Powered by Groq-hosted Large Language Models
- Dynamic model selection
- Fast response generation

### 🌐 Web Search Agent
- Real-time information retrieval using Tavily Search
- Retrieves and summarizes relevant web content
- Provides up-to-date responses beyond the LLM's training data

### 📰 AI News Summarizer
- Fetches the latest AI news using Tavily Search
- Generates concise AI-powered summaries
- Highlights key developments and trends

### 🔄 Workflow Orchestration
- Built using LangGraph
- Graph-based execution pipelines
- Modular architecture
- Stateful workflow management

---

## 🏗️ Architecture

```text
User
 │
 ▼
Streamlit Frontend
 │
 ▼
Use Case Router
 │
 ├── AI Chatbot
 ├── Web Search Agent
 └── AI News Summarizer
          │
          ▼
      LangGraph
          │
          ▼
       Groq LLM
          │
          ▼
       Response
```

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### AI Frameworks
- LangGraph
- LangChain

### LLM Provider
- Groq

### Search Tool
- Tavily Search API

### Language
- Python

---

## 📂 Project Structure

```bash
Multi-Agent-AI-Platform/
│
├── src/
│   ├── graph_builder/
│   ├── nodes/
│   ├── tools/
│   ├── llms/
│   ├── usecases/
│   └── utils/
│
├── app.py
├── requirements.txt
├── .env
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/KAsHiSHSET/Multi-Agent-AI-Platform.git

cd Multi-Agent-AI-Platform
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
TAVILY_API_KEY=your_tavily_api_key
```

### Run the Application

```bash
streamlit run app.py
```

---

## 🎯 Use Cases

### AI Chatbot
A conversational AI assistant capable of answering user queries using Groq-hosted LLMs.

### Chatbot With Web Search
Combines LLM reasoning with Tavily Search to retrieve real-time information from the web.

### AI News Summarizer
Fetches and summarizes the latest AI news articles, providing concise and relevant updates.

---

## 📚 Key Learnings

- Agentic AI Systems
- LangGraph Workflow Design
- State Management in AI Applications
- Tool Calling and Search Integration
- LLM Orchestration
- Streamlit Application Development
- Modular AI Architecture

---

## 🔮 Future Enhancements

- Retrieval-Augmented Generation (RAG)
- PDF Question Answering
- Vector Databases (FAISS / ChromaDB)
- Multi-Agent Collaboration
- Long-Term Memory
- Autonomous Task Planning

---

## 👨‍💻 Author

**Kashish Seth**

- GitHub: https://github.com/KAsHiSHSET
- LinkedIn: Add your LinkedIn profile

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
