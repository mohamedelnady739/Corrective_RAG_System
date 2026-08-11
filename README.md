# Corrective RAG System 📚

A Corrective Retrieval-Augmented Generation system that answers questions from PDF documents.

The system:
- Retrieves relevant document chunks.
- Evaluates the retrieved context.
- Rewrites the question when the context is weak.
- Retrieves again.
- Generates answers using verified context.
- Shows the document sources.

## Technologies

- Python
- LangChain
- FAISS
- HuggingFace Embeddings
- Google Gemini
- Streamlit

## Dataset

Kaggle Dataset:
https://www.kaggle.com/datasets/rohanthoma/ebook-pdfs
