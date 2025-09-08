# 🧠 RAG Pipeline with Google Gemma-3-270M-IT

This repository demonstrates how to build a **Retrieval-Augmented Generation (RAG)** system using the [Google Gemma-3-270M-IT](https://huggingface.co/google/gemma-3-270m-it) model from Hugging Face.  
The pipeline retrieves relevant documents, injects them into the prompt, and generates grounded answers with citations and optional summarization.

---

## 🚀 Features
- 🔎 **Retriever**: Fetches top-k relevant documents from a vector store.  
- 💡 **Gemma LLM**: Uses `google/gemma-3-270m-it` for local inference.  
- 📚 **Context Injection**: Passes retrieved context into the LLM prompt.  
- 🔗 **Citations**: Includes sources in the final answer.  
- 📝 **Summarization**: Optional concise answer summary.  
- 📜 **History Tracking**: Keeps track of queries, answers, and sources.  
- ⏳ **Streaming Simulation**: (Optional) prints responses progressively.  

