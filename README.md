# 🤖 AI Support Assistant – RAG + Streamlit

A lightweight AI-powered assistant built with OpenAI + Qdrant, designed to summarize logs, analyze tickets, and offer intelligent support resolutions in real time.

---

## 🔍 Key Features

- 🔎 RAG (Retrieval-Augmented Generation) using OpenAI & Qdrant
- 🧠 NLP-powered log summarization and querying
- 📊 Streamlit-based interactive UI
- 📁 Supports PDF, DOCX, and plain text ingestion
- ⚙️ Modular `rag_engine.py` for easy backend logic

---

## 🧱 Architecture

![Architecture](./assets/architecture.png)

---

## 🚀 Quick Start

```bash
git clone https://github.com/yourusername/ai-support-assistant.git
cd ai-support-assistant
pip install -r requirements.txt
streamlit run app/main.py
