# 📄 AutoRAG Assistant: Chat with your PDFs using Gemini 💬

This is a personal project that allows you to interact with PDF files using Google Gemini's language model. It uses LangChain to create a Retrieval-Augmented Generation (RAG) pipeline and FAISS for fast document retrieval.

Upload any PDF, ask questions, and get answers based on the document's content!

## Features
- Upload and process multiple PDFs
- Chunking and embedding using Gemini's `embedding-001`
- Semantic search with FAISS
- Context-aware answers from `gemini-pro` model
- Simple Streamlit interface

> This project was built for learning purposes with help from tutorials. Feel free to explore and modify!

## Tech Stack
- Python, Streamlit
- LangChain, FAISS
- Gemini
- PyPDF2, dotenv

## Setup
1. Clone the repo
2. Install requirements: streamlit, PyPDF2, langchain, faiss
3. Add your `GOOGLE_API_KEY` to a `.env` file
4. Run with `streamlit run app.py`

