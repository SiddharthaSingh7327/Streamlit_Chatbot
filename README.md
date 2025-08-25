# Enhanced Document Q&A Chatbot

This project is a **Streamlit-based chatbot** that allows you to upload documents (text, PDF, Word, images, etc.) and ask questions about their content.  
It uses **Google Gemini (multimodal)** for text + image understanding and **fast-GraphRAG** for building a knowledge graph of text-based documents.

---

## Features

- **Multi-format document support**:
  - `.txt`, `.md`, `.py`, `.js`, `.html`, `.css`, `.json`
  - `.pdf` (with text + image extraction)
  - `.docx`
  - `.jpg`, `.jpeg`, `.png` (image Q&A with Gemini)

- **Knowledge graph generation** with `fast-graphrag` for text documents.
- **Gemini multimodal queries** for documents with images.
- **Chat history** to maintain conversation context.
- **Streamlit UI** with sidebar controls:
  - Upload documents
  - View extracted text and images
  - Regenerate knowledge graph
  - Clear chat history

---
