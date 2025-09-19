# langchain-pdf-rag
"A LangChain-powered RAG chatbot that reads PDFs, performs OCR if needed, embeds text with HuggingFace, and answers user queries with Gemini + web search context."

# PDF-RAG-Chatbot

A **LangChain-powered RAG chatbot** that lets you chat with your PDFs.  
It supports OCR for scanned PDFs, uses HuggingFace embeddings for vector search,  
and answers your questions using **Gemini + web search context**.

---

## 🚀 Features

- 📄 **PDF Support** – Reads normal and scanned PDFs (OCR fallback included)  
- 🔍 **Chunking & Embeddings** – Splits PDFs into chunks and embeds with `all-mpnet-base-v2`  
- 🧠 **Context-Aware Responses** – Uses LangChain + Chroma vector store  
- 🌐 **Web Search** – Optionally fetches extra context from the web (Serper API)  
- 🤖 **LLM-Powered Answers** – Gemini (Google Generative AI) provides final responses  

---

## 🛠️ Installation

1. **Clone the repo**
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

