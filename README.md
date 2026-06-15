# Conversational-RAG-Chatbot

Conversational Q&A Chatbot with LangChain

This project demonstrates how to build a Conversational Q&A Chatbot with memory using LangChain, open-source LLMs, and vector databases (ChromaDB).

The chatbot is capable of:

Answering questions based on external data (web pages)
Maintaining conversation history
Understanding follow-up queries using context-aware retrieval
🚀 Features

✅ Conversational Q&A with memory
✅ History-aware retriever (context understanding)
✅ Retrieval-Augmented Generation (RAG) pipeline
✅ Uses open-source models (no OpenAI dependency)
✅ Web-based data ingestion
✅ Vector storage using ChromaDB
✅ HuggingFace embeddings

🏗️ Architecture Overview

User Query

  ↓

History-Aware Retriever

  ↓

Vector Store (ChromaDB)

  ↓

Retrieved Documents

  ↓

LLM (Llama-3 / Groq)

  ↓

Final Answer (with context + memory)

📦 Tech Stack

LangChain
Groq (Llama-3 model)
HuggingFace Embeddings
ChromaDB
BeautifulSoup (bs4)
Python
