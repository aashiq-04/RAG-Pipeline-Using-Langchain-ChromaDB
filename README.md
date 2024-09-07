# RAG-Pipeline-Using-Langchain-ChromaDB

This repository implements a Retrieval-Augmented Generation (RAG) pipeline that combines Langchain and ChromaDB to enable efficient querying of PDF documents. It allows users to retrieve relevant sections from large PDFs and generate detailed responses using natural language models.

## Features

- **Document Processing**: Load, split, and preprocess documents.
- **Vector Embeddings**: Use Hugging Face's sentence-transformers for generating embeddings.
- **ChromaDB Integration**: Store and retrieve documents efficiently using ChromaDB.
- **Question Answering**: Retrieve relevant context from documents and answer queries using LangChain.

## Requirements

- Python 3.8+
- Hugging Face Transformers
- Install the required libraries using the following command:

```bash
pip install -r requirements.txt
```
