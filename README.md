# 🩺 Healthcare AI Assistant

A Retrieval-Augmented Generation (RAG) based medical chatbot that answers healthcare-related questions using medical documents and Large Language Models (LLMs).

## Features

* Medical Question Answering
* Semantic Search with Pinecone
* GPT-4o Powered Responses
* LangChain RAG Pipeline
* Context-Aware Answer Generation

## Tech Stack

* Python
* LangChain
* OpenAI GPT-4o
* Pinecone
* Hugging Face Embeddings

## How It Works

1. User submits a medical query.
2. Query is converted into embeddings.
3. Pinecone retrieves the most relevant medical document chunks.
4. GPT-4o generates an answer using the retrieved context.
5. The system returns a context-grounded response to the user.

## Run Locally

```bash
git clone <repository-url>
cd healthcare-ai-assistant
pip install -r requirements.txt
python app.py
```

Create a `.env` file:

```env
PINECONE_API_KEY=your_key
OPENAI_API_KEY=your_key
```
