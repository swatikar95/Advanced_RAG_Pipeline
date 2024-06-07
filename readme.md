### RAG Pipelines for Large Language Modeling(LLM)

This repository contains implementations of basic and advanced Retrievel Augmented Generator (RAG) pipelines used for LLM tasks. The RAG approach combines the strengths of dense retrievers and powerful language models to generate informative, contextually relevant responses.

### Overview

`RAG_pipeline.ipynb`: Implements the basic RAG pipeline.

`auto_merging_retrieval.ipynb`: Features an advanced RAG pipeline with auto-merging retrieval capabilities, which essentially utilizes different chunk sizes at various layers. The model is evaluated by computing 'Answer Relevance', 'Context Relevance' and 'Groundedness'. 

`sentence_window_retrival.ipynb`: Demonstrates sentence window retrieval technique, which optimizes the context window for better performance in retrieval tasks.This model is also evaluated by computing 'Answer Relevance', 'Context Relevance' and 'Groundedness'.