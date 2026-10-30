# Document Question Answering with LangChain

## Overview
This project explores building document processing and question-answering workflows using Large Language Models (LLMs) and LangChain.

It covers loading data from multiple sources, splitting text into chunks, generating embeddings, storing vector representations, and exploring different question-answering chains.

## Technologies
- Python
- LangChain
- OpenAI API
- Hugging Face
- Cohere
- FAISS
- Chroma
- NLTK
- TikToken

## Project Workflow

### 1. Document Loading
Explored loading documents and data from:
- Pandas DataFrames
- Web URLs
- Wikipedia
- PDF files
- Directories

### 2. Text Splitting
Explored different text-splitting approaches:
- Character-based text splitting
- NLTK-based splitting
- Token-based splitting using TikToken
- Transformer tokenizer-based splitting

### 3. Text Embeddings
Explored embedding models and providers:
- OpenAI Embeddings
- Hugging Face Embeddings
- Cohere Embeddings

### 4. Vector Stores
Explored vector storage and retrieval using:
- FAISS
- Chroma

### 5. Question Answering Chains
Explored different LangChain chain strategies:
- Stuff
- MapReduce
- Refine

## Project Structure
- `document_qa_langchain.ipynb`: Jupyter Notebook containing the experiments and implementation examples.

## Learning Objectives
- Understand document loading and preprocessing.
- Learn how text chunking supports LLM applications.
- Explore text embeddings and vector stores.
- Understand different question-answering chain strategies.

## Author
Saeed Al-Sayed
