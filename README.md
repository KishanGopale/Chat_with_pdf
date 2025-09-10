# Chat_with_pdf
Upload your pdf and chat with LLM that can give your pdf related answers

# 📚 Mini LLM with RAG Pipeline

A small **LLM-powered chatbot** that lets users upload PDFs and ask questions.  
The system retrieves relevant content from the PDF using **embeddings + vector search**, and generates answers using a **Groq-hosted LLM**.

---

## 📖 Overview
This project demonstrates how to build a **Retrieval-Augmented Generation (RAG)** pipeline for document Q&A.  
The workflow:
1. User uploads a PDF.  
2. Text is chunked and converted into embeddings.  
3. Embeddings are stored/retrieved from **Pinecone vector database**.  
4. A query is matched with relevant chunks.  
5. **Groq LLM API** generates a contextual answer.  
6. Results are displayed in a **Streamlit UI**.  

---

## ⚙️ Tools & Technologies
- **LLM**: Groq API (chat model)  
- **Embeddings**: Cohere (Multilingual model, dim=1024)  
- **Vector Database**: Pinecone  
- **Frontend/UI**: Streamlit  
- **Language**: Python 3.9+  

---

## 🛠 Features
- Upload PDFs and chat with them.  
- Multilingual support via Cohere embeddings.  
- Fast and scalable search with Pinecone.  
- Simple and interactive Streamlit interface.  

---


cd mini-llm-rag

