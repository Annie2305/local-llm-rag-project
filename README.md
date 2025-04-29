# Local LLM Resume Retrieval (RAG Project)

This project demonstrates how to build a local Retrieval-Augmented Generation (RAG) system using Ollama and LangChain.  
The goal is to retrieve and answer questions based on resume or document content, running fully on local devices.

## Project Structure (Three Phases)

**Phase 1 – Build RAG from Scratch**
- Deploy a local LLM model (Deepseek R1 7B) via Ollama.
- Parse text files manually into paragraphs.
- Convert each paragraph into embeddings using Ollama API.
- Manually implement similarity search (cosine similarity) to retrieve the most relevant content.

**Phase 2 – Enhance RAG with LangChain Framework**
- Use LangChain modules to automate document parsing, chunking, embedding, and retrieval.
- Store embeddings in Chroma vector database for efficient similarity search.
- Use retrieval chains to integrate the search and LLM answering processes.

**Phase 3 – Extend to Support PDF Documents**
- Load and split PDF files into text chunks.
- Embed PDF content and store vectors in Chroma.
- Enable users to ask questions based on both text and PDF sources.

## Features
- Local LLM deployment with Ollama.
- Text and PDF document retrieval and question answering.
- Interaction via terminal interface.
- Modular design for future extension and scaling.

