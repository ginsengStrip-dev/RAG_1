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

## 🚀 Installation

Follow these steps to set up the project locally:

### 1. Clone the repository
```bash
git clone https://github.com/ginsengStrip-dev/RAG_1.git
```
### 2. Navigate to the project folder
```bash
cd RAG_1
```
### 3. (Optional) Create and activate a virtual environment
```bash
# For Linux / Mac
python -m venv venv
source venv/bin/activate

# For Windows
python -m venv venv
venv\Scripts\activate
```
### 4. Install dependencies
```bash
pip install -r requirements.txt
```
