# 🎥 YouTube RAG Chatbot (Gemini + Whisper + FAISS)

This project is a **Retrieval-Augmented Generation (RAG) system** that allows users to chat with YouTube videos.

---

## 🚀 Features
- YouTube video → audio extraction
- Whisper speech-to-text transcription
- Text chunking for better retrieval
- Embeddings using Sentence Transformers
- FAISS vector database for similarity search
- Gemini LLM for answering questions

---

## 🧠 Pipeline

YouTube Video  
→ Audio (yt-dlp)  
→ Whisper Transcription  
→ Chunking  
→ Embeddings  
→ FAISS Vector DB  
→ Gemini LLM Answer

---

## 🛠️ Tech Stack
- Python
- Whisper AI
- yt-dlp
- LangChain
- FAISS
- Google Gemini API
- Streamlit / Gradio (future UI)

---

## 📦 How to Run

```bash
pip install -r requirements.txt
