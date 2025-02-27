# DeepSeek AI - Smart Code Navigator & DocuMind AI

## Overview
This repository contains two AI-powered applications built using **Streamlit, LangChain, and Ollama**:

1. **DeepSeek AI (Smart Code Navigator)** - An **AI coding assistant** that helps with debugging, code explanations, and development suggestions.
2. **DocuMind AI (RAG-based Document Assistant)** - A **PDF research assistant** that extracts insights from documents using a Retrieval-Augmented Generation (RAG) approach.

## Features
### **DeepSeek AI (Coding Assistant)**
- ✅ AI-powered **code debugging & recommendations**
- ✅ **Supports multiple models** (`deepseek-r1:1.5b`, `deepseek-r1:3b`)
- ✅ **Interactive Chat UI** built with Streamlit
- ✅ **Customizable prompt pipeline** using LangChain
- ✅ **Strategic print statements for debugging assistance**

### **DocuMind AI (RAG Assistant)**
- 📄 **Upload PDFs & Extract Key Insights**
- 🧠 **Retrieves relevant document sections** for user queries
- ⚡ **Fast & Memory-efficient** document chunking
- 🔍 **Search through indexed knowledge** using embeddings
- 🤖 **Built with DeepSeek LLM (Ollama)**

---

## Installation & Setup

### **1. Clone the Repository**
```sh
git clone https://github.com/yourusername/DeepSeek-RAG-AI.git
cd DeepSeek-RAG-AI
```

### **2. Install Dependencies**
```sh
pip install -r requirements.txt
```

### **3. Start the AI Code Assistant**
```sh
streamlit run app.py
```

### **4. Start the RAG-based Document Assistant**
```sh
streamlit run rag_deep.py
```

---

## Usage Guide

### **DeepSeek AI - Smart Code Navigator**
1. Select a **DeepSeek model** (`deepseek-r1:1.5b` or `deepseek-r1:3b`).
2. Type your **coding question or debugging issue** in the chat.
3. The AI will provide solutions, explanations, and debugging help.

### **DocuMind AI - Document Research Assistant**
1. Upload a **PDF research document**.
2. Ask a question related to the document.
3. The AI will retrieve **relevant sections** and provide an answer.

---

## File Structure
```
DeepSeek-RAG-AI/
│── app.py              # AI-powered coding assistant
│── rag_deep.py         # RAG-based document research assistant
│── requirements.txt    # Required dependencies
│── document_store/     # Stores uploaded PDFs
└── README.txt          # Project documentation
```

---

## Dependencies
- **Python 3.8+**
- **Streamlit** (for UI)
- **LangChain** (for AI pipelines)
- **Ollama** (DeepSeek AI models)
- **PDFPlumber** (for document processing)

---

## Future Improvements
- 🔄 **Add FAISS/ChromaDB** for persistent document storage
- ⚡ **Optimize response latency** for large documents
- 📡 **Extend AI models** to more coding languages & research fields

---

## Contributing
Feel free to fork this repository and submit a pull request! 🚀

---

## License
MIT License © 2025 Rofiqul Alam Shehab

