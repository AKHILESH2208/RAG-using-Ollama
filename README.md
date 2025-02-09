## RAG-using-Ollama

![image](https://github.com/user-attachments/assets/f87e2ac9-0334-4f66-9bbf-6f955a6578c3)

This project implements a Retrieval-Augmented Generation (RAG) pipeline using Ollama for embedding and generation, and FAISS (via Chroma DB) for efficient vector storage and retrieval. The pipeline processes PDFs, extracts and chunks text, stores it in a vector database, retrieves relevant documents for queries, and generates responses.

# Features
Extracts text from PDFs in the books/ directory.

Chunks text for efficient embedding.

Uses OllamaEmbeddings for vector representation.

Stores and retrieves embeddings using FAISS (via Chroma DB).

Implements MultiQueryRetriever for enhanced retrieval.

Generates responses using ChatOllama.


## Installation
Copy and run the following command:

```bash
pip install langchain chromadb pypdf unstructured ollama
