# RAG Search Pipeline

## Overview

This project demonstrates a simple end-to-end Retrieval-Augmented Generation (RAG) pipeline built in Python.

The pipeline retrieves relevant information from a document using semantic search and keyword search, combines the results using hybrid retrieval, reranks the best chunks, and passes the retrieved context to a language model to generate a grounded answer.

## Key Features

- Document ingestion
- Text cleaning
- Fixed-size chunking
- Sentence Transformer embeddings
- ChromaDB vector storage
- Semantic / vector search
- BM25 keyword search
- Hybrid search
- Top-K retrieval
- Cross-Encoder reranking
- Context retrieval
- LLM-based answer generation

## Tech Stack

- Python
- Jupyter Notebook
- Sentence Transformers
- ChromaDB
- BM25
- scikit-learn
- NumPy

## RAG Pipeline

Document  
→ Cleaning  
→ Chunking  
→ Embeddings  
→ ChromaDB  
→ Vector Search + BM25  
→ Hybrid Search  
→ Top-K Results  
→ Cross-Encoder Reranking  
→ Retrieved Context  
→ Prompt  
→ LLM  
→ Final Answer

## Example Query

**Question:**  
What are the company's plans for Singapore in 2027?

**Answer:**  
Expand into Singapore.

## Project Structure

```text
rag-search-pipeline/
├── data/
│   └── rag_sample.txt
├── notebooks/
│   └── rag_search_pipeline.ipynb
└── README.md
