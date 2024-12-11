# RAG for LLMs: Semantic Search and Question Answering

## Overview
This repository contains two labs that explore Retrieval-Augmented Generation (RAG) for language models. They are part of the RAG course at Université Paris Cité for the 2024-2025 academic year. It focuses on understanding and implementing RAG pipelines, with practical applications in semantic search and domain-specific question answering. The two labs involve building retrievers, experimenting with vector databases, and evaluating end-to-end RAG systems.

## Contents
### 1. Lab1: Semantic Search
Implements a retriever-based semantic search pipeline using sentence transformers.
- Retriever Implementation
- Sentence Transformer Pipeline
  
### 2. Lab2: Small RAG for Question Answering
Build a simplified RAG system to answer domain-specific questions (e.g., Warhammer 40K rules) using a lightweight, quantized LLama 3.2 1B model.
- Import and template the Llama 3.2 model for interactive Q&A.
- Experiment with ChromaDB for vector-based retrieval.
- Enhance retriever performance using headers and BM25.

## Required libraries
sentence-transformers, ChromaDB, and other dependencies specified in the notebooks
