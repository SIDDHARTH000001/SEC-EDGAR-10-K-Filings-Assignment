# SEC EDGAR 10-K RAG System

This project implements a basic Retrieval-Augmented Generation (RAG) pipeline for querying SEC EDGAR 10-K filings.

## Models Tried
- **LLMs**: 
  - `gemini-2.5-flash`
  - `gpt-4o-mini`
- **Embeddings**:
  - `all-MiniLM-L6-v2` *(current solution)*
  - `paraphrase-multilingual-MiniLM-L12-v2`

## Current Approach
The system uses:
- **Embedding model**: `all-MiniLM-L6-v2`
- **Hybrid Search**: Dense embeddings + TF-IDF
