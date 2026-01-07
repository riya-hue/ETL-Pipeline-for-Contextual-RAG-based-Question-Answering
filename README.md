# ETL-Pipeline-for-Contextual-RAG-based-Question-Answering

This project implements an end-to-end ETL pipeline for building a Retrieval Augmented Generation (RAG) system.
The pipeline extracts unstructured text data, preprocesses and chunks it for LLM consumption, generates semantic embeddings, stores them in a vector database (FAISS), and retrieves relevant context to generate grounded responses using a lightweight LLM.

The system is designed to be fully runnable, explainable, and debuggable, focusing on practical AI engineering rather than theoretical concepts.

🏗️ System Architecture
Raw Text Data
   ↓
Text Cleaning & Normalization (Transform)
   ↓
Chunking with Overlap
   ↓
Embedding Generation (SentenceTransformers)
   ↓
Vector Storage (FAISS)
   ↓
Semantic Retrieval
   ↓
LLM Response Generation (RAG)

⚙️ Tech Stack

Language: Python

Embeddings: SentenceTransformers

Vector Database: FAISS

LLM: Hugging Face Transformers (FLAN-T5)

Numerical Processing: NumPy
