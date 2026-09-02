# 🤖 RAG-Powered Intelligent Document Query System (AI Agent)

An enterprise-ready Full-Stack Retrieval-Augmented Generation (RAG) application that enables users to upload custom PDF/text documents, generate vector embeddings, and query contextual insights using an intelligent AI agent setup.

---

## 📌 Features

* 📄 **Document Ingestion & Processing:** Supports PDF and TXT parsing with automated text chunking.
* ⚡ **Vector Embeddings & Retrieval:** Vector storage indexing using ChromaDB for fast semantic search.
* 🧠 **LLM Contextual QA:** Powered by LangChain and LLM APIs to generate accurate, hallucination-free responses based strictly on document context.
* 💬 **Interactive Chat UI:** Built with Streamlit for seamless user interaction and query tracking.
* 🔧 **REST-Ready Modular Architecture:** Clean, modular backend structure suitable for exposing REST endpoints.

---

## 🛠️ Tech Stack

* **Language:** Python
* **LLM & Agent Framework:** LangChain, OpenAI API
* **Vector Store:** ChromaDB
* **User Interface:** Streamlit
* **Utilities:** PyPDF2, python-dotenv

---

## 📂 Project Structure

```text
├── app.py                 # Streamlit UI & interface logic
├── rag_engine.py          # Core RAG pipeline (chunking, embeddings, vectorstore)
├── requirements.txt       # Dependencies
├── .env.example           # Environment variables template
└── README.md              # Documentation
