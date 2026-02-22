# multi-source-ai-assistant
AI-Powered Natural Language Data Query App  A lightweight GenAI project that lets users query structured data (Excel/PDF) using plain English. Built with Python and Gradio, the app parses natural language (e.g., “above 500”, “near 100”) .
# 🧠 Multi-Source Personal AI Assistant

A hybrid GenAI system that intelligently routes user queries between structured transaction analytics and multi-document RAG.

Built to demonstrate production-style AI system design beyond basic chatbots.

---

## 🚀 Overview

This project combines rule-based intelligence with Retrieval-Augmented Generation (RAG) to answer queries from multiple data sources.

The assistant:

- Detects transaction-related queries → uses structured analytics  
- Detects knowledge queries → uses vector search + LLM  
- Returns grounded, context-aware responses  
- Provides an interactive Gradio interface  

---

## 🏗️ Architecture

**Query Flow**

User Query  
→ Intent Routing  
→ (Transactions Engine OR RAG Pipeline)  
→ Final Answer  

**RAG Pipeline**

- Multi-document ingestion  
- Recursive text chunking  
- HuggingFace embeddings  
- Chroma vector database  
- MMR retrieval  
- Gemini Flash LLM  
- Gradio UI  

---

## ✨ Key Features

- Hybrid routing (Rules + RAG)
- Multi-format data ingestion (PDF, Excel)
- Natural language transaction queries
- Vector similarity search with ChromaDB
- MMR retrieval for diverse context
- Modular and extensible design
- Interactive Gradio interface

---

## 📊 Example Queries

### 💳 Transactions

- Payments above 50000  
- Total spending  
- Transactions on 2025-09-24  
- What did I pay near 2000  

### 📚 RAG

- What are AWS Well-Architected best practices?  
- Summarize general design principles  
- Compare AWS vs Azure security guidance  

---

## 🛠️ Tech Stack

- Python  
- LangChain  
- ChromaDB  
- HuggingFace Embeddings  
- Google Gemini Flash  
- Pandas  
- Gradio  

---

## 📁 Project Structure
