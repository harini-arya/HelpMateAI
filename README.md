

# HelpMate AI - RAG-based Intelligent Assistance

## Overview
HelpMate AI is a **Retrieval-Augmented Generation (RAG) system** designed to enhance knowledge retrieval and response generation. It utilizes **ChromaDB** for vector-based search, **pdfplumber** for document parsing, and **OpenAI’s API** for advanced text processing.

## Features
- **PDF Knowledge Extraction**: Extracts content from PDF files using `pdfplumber`.
- **Vector Database Search**: Uses `ChromaDB` for efficient similarity-based retrieval.
- **Embedding Generation**: Utilizes `tiktoken` and OpenAI's embedding models for optimized text representation.
- **RAG-based Response Generation**: Combines retrieved knowledge with GPT-based response generation.

## Dependencies
Install required dependencies using:
```bash
pip install pdfplumber chromadb tiktoken openai pandas
``` 

## Usage
1. **Upload PDF documents** – Add PDF files for processing.  
2. **Extract text and store embeddings** – Use `pdfplumber` to extract text and store embeddings in `ChromaDB`.  
3. **Query the system** – Retrieve relevant information and generate intelligent responses using OpenAI’s API.  

## Technologies Used
- **Python**  
- **Google Colab**  
- **ChromaDB**  
- **OpenAI API**  
- **pdfplumber**  
- **tiktoken**  
