# RAG_chat_app

# 📚 Document Chat App

This is a Streamlit-based application that allows users to upload documents (PDF, DOCX, TXT) and interactively ask questions based on the uploaded content. The app uses a combination of FAISS for semantic search and a T5 transformer model for response generation.

## 🔧 Features

* 📄 Supports PDF, DOCX, and TXT file uploads.
* 🧠 Embeds and indexes content using SentenceTransformer.
* 🔍 Retrieves relevant chunks using FAISS similarity search.
* 🗨️ Generates context-aware answers using T5 model.
* ⚡ Fast and interactive UI with Streamlit.

## 🛠️ Technologies Used

* **Python**
* **Streamlit**
* **Transformers (T5-small)**
* **Sentence-Transformers (all-MiniLM-L6-v2)**
* **FAISS**
* **PyPDF2**, **python-docx**

## ▶️ How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SAMUDRAGUPTA002/RAG_chat_app.git
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app:**

   ```bash
   streamlit run rag_app.py
   ```

4. **Usage:**

   * Upload PDF, DOCX, or TXT files.
   * Ask any question related to the uploaded documents.
   * Get AI-generated responses and see relevant excerpts.

## 📂 File Structure

```
rag_app.py           # Main Streamlit application
README.md            # Project documentation
requirements.txt     # Required Python packages
```

## 📄 License

This project is licensed under the **MIT License**. Feel free to use and modify.

