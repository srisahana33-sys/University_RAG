# University RAG Chatbot

A Retrieval-Augmented Generation (RAG) chatbot that answers university-related queries using custom documents instead of relying solely on a Large Language Model. This project demonstrates how semantic search, vector databases, reranking, and Google's Gemini API can be combined to build an accurate and context-aware question answering system.

---

## Features

-  Upload and process university documents
-  Intelligent document chunking
-  Semantic search using FAISS
-  Embedding generation with Sentence Transformers
-  Cross-Encoder reranking for improved retrieval accuracy
-  Answer generation using Gemini
-  Context-aware responses with source-grounded information
-  Easy-to-follow implementation in Google Colab

---

## Tech Stack

- Python
- Google Colab
- LangChain
- FAISS
- Sentence Transformers
- Cross Encoder
- Google Gemini API
- Hugging Face
- Pandas

---

## Project Workflow

```
University Documents
        │
        ▼
Document Loading
        │
        ▼
Text Chunking
        │
        ▼
Embedding Generation
        │
        ▼
FAISS Vector Store
        │
        ▼
User Question
        │
        ▼
Semantic Retrieval
        │
        ▼
Cross-Encoder Reranking
        │
        ▼
Gemini LLM
        │
        ▼
Final Response
```

---

##  How It Works

1. Load university-related documents.
2. Split the documents into smaller chunks.
3. Generate embeddings using a Sentence Transformer model.
4. Store the embeddings inside a FAISS vector database.
5. When a user asks a question, retrieve the most relevant chunks.
6. Rerank the retrieved results using a Cross-Encoder.
7. Pass the highest-ranked context to Gemini.
8. Generate an accurate, context-aware answer.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/University_RAG.git
cd University_RAG
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure your Gemini API key before running the notebook.

---

## Running the Project

Open the notebook in Google Colab and execute each cell in order.

The notebook handles:

- Loading documents
- Creating embeddings
- Building the FAISS index
- Retrieving relevant context
- Generating responses using Gemini

---

## Future Improvements

- Web interface using Streamlit
- Multi-document upload
- Conversation memory
- Hybrid keyword + semantic search
- Citation highlighting
- Support for multiple universities

---

