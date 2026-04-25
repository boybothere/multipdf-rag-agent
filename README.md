# Chat with Multiple PDFs using Gemini 

A robust, production-grade Retrieval-Augmented Generation (RAG) application built with Streamlit, LangChain, and Google's Gemini API. Upload multiple PDF documents, process them into a local vector database, and instantly chat with your data to extract insights, timelines, and precise answers based *only* on the provided context.

## App Screenshot
<img width="1831" height="900" alt="image" src="https://github.com/user-attachments/assets/5482ad7a-f55b-48a7-91b8-56b81aaf2e0f" />


## Features

* **Multi-Document RAG:** Upload and process multiple PDFs simultaneously.
* **Modern LangChain Architecture:** Built using the latest LangChain modular packages (`langchain-community`, `langchain-google-genai`, `langchain-text-splitters`).
* **High-Speed Inference:** Powered by Google's `gemini-2.5-flash` model and the `gemini-embedding-001` embedding model.
* **Local Vector Storage:** Uses FAISS (Facebook AI Similarity Search) to build a fast, localized index of your documents directly in your environment.
* **Interactive UI:** Clean, user-friendly sidebar for document uploading and processing, with a main chat interface for queries.

## Tech Stack

* **Frontend:** [Streamlit](https://streamlit.io/)
* **AI/LLM:** [Google Gemini API](https://ai.google.dev/)
* **Orchestration:** [LangChain](https://python.langchain.com/)
* **Vector Database:** [FAISS](https://faiss.ai/)
* **PDF Parsing:** [PyPDF2](https://pypdf2.readthedocs.io/)

## Installation & Setup

**1. Clone the repository**
```bash
git clone [https://github.com/boybothere/multipdf-rag-agent.git](https://github.com/boybothere/multipdf-rag-agent.git)
cd multipdf-rag-agent
