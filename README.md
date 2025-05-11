# RAG_Resume

This repository demonstrates how to apply Retrieval-Augmented Generation (RAG) to resume understanding and question answering.

## Overview

The goal of this project is to explore how RAG can be used to improve resume-based Q&A by combining retrieval techniques with large language models (LLMs). The notebook implements a pipeline that retrieves relevant text chunks from resumes and feeds them to a language model for grounded generation.

## Key Components

- Resume preprocessing and chunking
- Embedding and indexing using FAISS
- Dense or hybrid retrieval setup
- Prompt construction with retrieved resume context
- Generative model answering based on context

## Technologies Used

- Python
- Jupyter Notebook
- Hugging Face Transformers
- FAISS
- LangChain
- LLaMA
