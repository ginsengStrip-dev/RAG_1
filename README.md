📚 PDF Research Assistant (RAG with Gemma + ChromaDB)

A Retrieval-Augmented Generation (RAG) system built in Python to query research papers (PDFs) using local Hugging Face LLMs (Gemma 270M-IT).
The pipeline extracts text from PDFs, generates embeddings, stores them in ChromaDB, and retrieves context to answer questions with citations.

✨ Features

📄 PDF ingestion with text chunking

🔎 Semantic search with embeddings (all-MiniLM-L6-v2)

🧠 MMR re-ranking for diverse retrieval

📑 Citations in answers ([filename - page])

🗂 Persistent vector store with ChromaDB

🤖 Local LLM (Gemma 3 270M-IT) with safe prompt handling

🛡 Fallback if no relevant context is found
