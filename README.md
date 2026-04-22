# RAG Pipeline Implementation

This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline built using LangChain, Hugging Face embeddings, ChromaDB, and Groq LLMs.

## What it does
- Loads PDF/text documents
- Splits them into chunks
- Converts text into embeddings using Hugging Face models
- Stores embeddings in a vector database (ChromaDB)
- Retrieves relevant chunks based on user queries
- Generates answers using a Groq LLM

## Tech Stack
- Python
- LangChain
- ChromaDB
- Hugging Face Sentence Transformers
- Groq API

## Setup

1. Clone the repo
```bash
git clone https://github.com/your-username/RAG_Tutorial.git
cd RAG_Tutorial
```
2. Install dependencies:
`pip install -r requirements.txt`

3. Add API keys in .env:
```bash
GROQ_API_KEY=your_key_here
HUGGINGFACE_API_KEY=your_key_here
```

**NOTE:** You can replace the data folder with your own documents to test the pipeline.
