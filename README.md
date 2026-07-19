# AI_Research_Agent
# 🤖 Research Paper AI Agent

An Agentic AI-powered research assistant that helps users discover relevant research papers using semantic search, generate concise summaries, extract keywords, and answer research-related queries through LangChain agents.

---

## Overview

Traditional keyword-based search often misses relevant papers because it relies on exact word matching.

This project leverages modern NLP techniques and Agentic AI to understand the semantic meaning of a query, retrieve the most relevant papers, summarize them, and extract important concepts automatically.

---

## Features

- Semantic Search using Sentence Transformers
- Dense Vector Embeddings
- FAISS Vector Database
- Research Paper Retrieval
- Automatic Paper Summarization
- Keyword Extraction using KeyBERT
- LangChain Tool Calling
- Agentic AI Workflow
- Hugging Face Transformers Integration
- Groq LLM Integration

---

## Tech Stack

### Languages

- Python

### NLP

- Sentence Transformers
- Hugging Face Transformers
- KeyBERT

### Machine Learning

- Scikit-learn
- NumPy
- Pandas

### Vector Search

- FAISS

### Agent Framework

- LangChain
- LangChain Groq

### LLM

- Llama 3 (via Groq)

---

## Architecture

User Query

↓

Sentence Transformer

↓

Embedding Generation

↓

FAISS Vector Search

↓

Top-k Relevant Papers

↓

Summarization + Keyword Extraction

↓

LangChain Agent

↓

Final AI Response

---

## Project Workflow

1. Load Research Dataset

2. Clean and preprocess text

3. Generate embeddings using Sentence Transformers

4. Store embeddings in FAISS

5. Receive user query

6. Convert query into embedding

7. Retrieve similar papers

8. Summarize retrieved papers

9. Extract keywords

10. LangChain Agent decides which tool to invoke

11. Return final response

---

## Example Query

```
Find papers about reinforcement learning for robotics.
```

Output:

- Top relevant papers
- Similarity score
- AI-generated summary
- Important keywords

---

## Installation

```bash
git clone https://github.com/yourusername/Research-Paper-AI-Agent.git

cd Research-Paper-AI-Agent

pip install -r requirements.txt
```

---

## Run

Open

```
Research_Paper_AI_Agent.ipynb
```

or execute the Python modules individually.

---

## Requirements

- Python 3.10+
- FAISS
- Sentence Transformers
- Hugging Face Transformers
- LangChain
- Groq API Key

---

## Future Improvements

- RAG Pipeline
- Streamlit Interface
- PDF Upload Support
- Multi-document QA
- Citation Generation
- CrossEncoder Re-ranking
- ChromaDB/Pinecone Support
- Docker Deployment
- Cloud Deployment

---

## Learning Outcomes

This project helped me understand:

- Semantic Search
- Dense Embeddings
- Vector Databases
- FAISS Indexing
- Transformer Models
- LangChain Agents
- Tool Calling
- Agentic AI Systems
- LLM Integration
- Retrieval-Augmented Generation fundamentals

---

## License

MIT License
