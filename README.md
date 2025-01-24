# RAG-DeepSeek-Ollama

A Retrieval-Augmented Generation (RAG) system for PDF document analysis using DeepSeek-R1 and Ollama.

## Features
- PDF document ingestion and semantic chunking
- Vector embeddings with HuggingFace models
- FAISS vector store for efficient similarity search
- Customizable Streamlit UI with color theming
- RAG pipeline with DeepSeek-R1 via Ollama

## Prerequisites
- Ollama installed and running
- DeepSeek-R1 model installed (`ollama pull deepseek-r1`)
- Python 3.8+

## Installation
```bash
git clone https://github.com/yourusername/RAG-DeepSeek-Ollama-PDF.git
cd RAG-DeepSeek-Ollama-PDF
pip install -r requirements.txt
