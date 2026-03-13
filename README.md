$readme = @'
# Financial AI Chatbot - NeoStats Use Case

A Streamlit-based financial AI chatbot for Indian markets and companies, built with LangChain and Groq.

## Features
- Chat with AI about Indian markets and companies
- Concise and Detailed response modes
- PDF document upload with RAG (Retrieval Augmented Generation)
- Live web search using Tavily
- Powered by Llama 3.1 via Groq

## Tech Stack
- Streamlit
- LangChain
- Groq (llama-3.1-8b-instant)
- FAISS vector store
- HuggingFace embeddings
- Tavily web search

## Setup

1. Clone the repo
2. Install dependencies:
   pip install -r requirements.txt
3. Add your API keys in config/config.py:
   GROQ_API_KEY = "your_groq_key"
   TAVILY_API_KEY = "your_tavily_key"
4. Run the app:
   streamlit run app.py

## Project Structure
- app.py - Main Streamlit application
- config/config.py - API keys and prompts
- models/llm.py - Groq LLM setup
- models/embeddings.py - HuggingFace embeddings
- utils/rag_utils.py - PDF processing and retrieval
- utils/search_utils.py - Tavily web search
'@
$readme | Set-Content "C:\Users\abhis\Downloads\NeoStats AI Engineer Use Case\README.md" -Encoding UTF8
