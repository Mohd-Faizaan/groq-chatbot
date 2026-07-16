# Groq Chatbot

A Retrieval-Augmented Generation (RAG) chatbot built using **LangChain**, **Groq LLM**, **FAISS**, and **Streamlit**. The application retrieves relevant information from documents before generating accurate responses using Groq's Llama models.

## Features

- Groq LLM integration
- Retrieval-Augmented Generation (RAG)
- FAISS vector database
- Ollama Embeddings
- LangChain Retrieval Chain
- Streamlit web interface
- Document similarity search

## Tech Stack

- Python
- Streamlit
- LangChain
- Groq
- FAISS
- Ollama Embeddings
- Python Dotenv

## Project Structure

```
groq-chatbot/
│
├── app.py
├── .env
├── .gitignore
├── requirements.txt
└── README.md
```

## Installation

### Clone the repository

```bash
git clone https://github.com/<your-username>/groq-chatbot.git
cd groq-chatbot
```

### Create a Virtual Environment

```bash
python -m venv venv
```

Activate it (Windows):

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_PROJECT=Groq-Chatbot
LANGCHAIN_TRACING=true
```

## Run the Application

```bash
streamlit run app.py
```

The chatbot will open in your browser.

## Features Demonstrated

- LangChain Retrieval Chain
- Vector Search with FAISS
- Groq Llama Models
- Prompt Engineering
- Document Retrieval
- Streamlit UI

## Future Improvements

- PDF Upload Support
- Chat History
- Multiple Document Support
- Source Citations
- Persistent Vector Database

## Author

Mohd Faizaan

---

⭐ If you found this project useful, consider starring the repository.
