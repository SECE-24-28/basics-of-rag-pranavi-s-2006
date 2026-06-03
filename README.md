# PDF Question Answering System

A simple RAG-based application that allows users to upload a PDF and ask questions about its content. The system uses LangChain, Hugging Face Embeddings, and FAISS for semantic search and information retrieval.

## Features
- Upload PDF documents
- Extract and process text
- Generate embeddings using Hugging Face
- Store vectors in FAISS
- Perform semantic similarity search
- Retrieve relevant content for user queries

## Tech Stack
- Python
- LangChain
- FAISS
- Hugging Face Embeddings
- PyPDF

## Workflow
1. Upload PDF
2. Extract text
3. Split into chunks
4. Generate embeddings
5. Store in FAISS
6. Ask questions
7. Retrieve relevant content

## Installation

```bash
pip install langchain
pip install langchain-community
pip install faiss-cpu
pip install sentence-transformers
pip install pypdf
pip install langchain-huggingface
```

## Usage

Run the notebook and upload a PDF when prompted. Enter a question related to the document, and the system will return the most relevant sections.

## Future Improvements
- Gemini/GPT integration
- Multi-PDF support
- Streamlit web interface
- Conversational chatbot
- Source citations

## Author
Developed as a beginner-friendly Retrieval-Augmented Generation (RAG) project using LangChain and FAISS.
