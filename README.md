<img width="1908" alt="Image" src="https://github.com/user-attachments/assets/e2048661-3aa5-43c9-84c1-3adc9c245392" />

# 📚 RAG-Powered PDF Question Answering App

This is a Streamlit-based web application that allows users to upload PDF files and ask questions about their contents using **Retrieval-Augmented Generation (RAG)**. It combines powerful embedding and LLM capabilities from **Google Gemini** with **LangChain**, **FAISS**, and **PyPDF2** for efficient document querying.

---

## 🚀 Features

- 📄 Upload a PDF document
- 🔍 Extract and split PDF content into embeddings
- 🧠 Query documents using Google Gemini's large language model
- 📚 Semantic retrieval powered by FAISS
- 🖼️ Simple and sleek Streamlit interface

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| Streamlit | Web UI |
| PyPDF2 | PDF parsing |
| LangChain | LLM orchestration |
| FAISS | Efficient vector store for similarity search |
| Google Gemini (via `google-generativeai`) | LLM & Embeddings |
| python-dotenv | Manage API keys securely |

---

## 📦 Installation

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/pdf-rag-app.git
cd pdf-rag-app
