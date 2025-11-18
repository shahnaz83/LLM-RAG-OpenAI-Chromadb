# Retrieval-Augmented Question Answering (RAG) System using OpenAI & ChromaDB

This project demonstrates my ability to work with **Large Language Models (LLMs)** and implement a **Retrieval-Augmented Generation (RAG)** pipeline.

The system allows you to upload a PDF document (e.g., company reports, articles, or research papers), extract its text, generate semantic embeddings using **OpenAI’s `text-embedding-3-small` model**, and store them in a **vector database (ChromaDB)**.  
Then, when you ask a question in natural language, the system retrieves the most relevant text chunks and uses **GPT-3.5-turbo** to generate an accurate, context-aware answer.

###  Key Components:
- **PyMuPDF** → Extracts text content from PDF files  
- **OpenAI API** → Creates embeddings and generates answers using LLM  
- **ChromaDB** → Stores and retrieves semantic embeddings  
- **Colab-ready notebook** → Designed for reproducible experiments and demonstrations

### What I Learned / Demonstrated:
- Practical experience with **LLM pipelines**
- Implementation of **RAG (Retrieval-Augmented Generation)**
- Building a **semantic search engine** using embeddings
- Using **Python, ChromaDB, and OpenAI API** together
- Deploying and documenting code for reproducible results

###  How it Works:
1. Extracts text from an uploaded PDF.
