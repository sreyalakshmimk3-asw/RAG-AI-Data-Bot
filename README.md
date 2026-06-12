# 🤖 AI-Powered Data Bot (RAG Pipeline)

An advanced Retrieval-Augmented Generation (RAG) pipeline built using **Python, LangChain, and ChromaDB**, powered by the **Google Gemini API**. This bot allows users to upload local documents (PDF or TXT) and have intelligent, context-aware conversations with their data without manual searching.

---

## 🚀 Features
* **Semantic Document Search:** Splits data into small chunks and indexes them for precise information retrieval.
* **Vector Embeddings:** Uses open-source `sentence-transformers/all-MiniLM-L6-v2` for generating clean text embeddings.
* **Local Vector Store:** Powered by `ChromaDB` for efficient vector similarity search.
* **Grounded LLM Responses:** Integrated with Google Gemini API (`gemini-2.5-flash`) with strict prompt constraints to avoid AI hallucinations.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Framework:** LangChain & LangChain-Community
* **Vector Store:** ChromaDB
* **Embeddings:** HuggingFace Sentence Transformers
* **LLM:** Google Gemini API

---

## 💻 How to Run

1. Clone this repository or open the provided script in Google Colab.
2. Install the required dependencies:
   ```bash
   pip install langchain langchain-community langchain-text-splitters chromadb sentence-transformers pypdf google-generativeai langchain-google-genai
