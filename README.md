# 📚 Multi-PDF Gen AI Chatbot

A Streamlit-based Gen AI chatbot that enables natural language querying over **multiple PDF documents**, powered by **LangChain**, **OpenAI**, and **Chroma**. This application uses LLMs and vector-based retrieval to deliver accurate, context-aware answers from uploaded PDFs.

---

## 🚀 Features

- 🔹 Upload and process multiple PDF files  
- 🔹 Extract and chunk text using `RecursiveCharacterTextSplitter`  
- 🔹 Generate vector embeddings via OpenAI  
- 🔹 Store and search documents with `Chroma` vector store  
- 🔹 Query your PDFs using natural language  
- 🔹 Fast and responsive UI built with Streamlit  

---

## 🧱 Tech Stack

- [Streamlit](https://streamlit.io/) – UI for interacting with the chatbot  
- [LangChain](https://www.langchain.com/) – Framework for building LLM applications  
- [OpenAI](https://openai.com/) – Embeddings and LLM provider  
- [Chroma](https://www.trychroma.com/) – Local vector store for efficient retrieval  
- [PyPDF2](https://pypi.org/project/PyPDF2/) – PDF text extraction  

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/pdf-chat-ai.git
cd pdf-chat-ai
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the app

```bash
streamlit run app.py
```

---

## 📝 License

This project is released under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🙏 Acknowledgments

- [LangChain](https://www.langchain.com/)  
- [OpenAI](https://openai.com/)  
- [Chroma](https://www.trychroma.com/)

---

## 🌟 Give it a star!

If you find this project useful, don't forget to give it a star on [GitHub](https://github.com/your-username/pdf-chat-ai)!

---