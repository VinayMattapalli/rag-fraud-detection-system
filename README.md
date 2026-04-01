RAG-Based Fraud Detection System

This project implements a real-time fraud detection system using Machine Learning and Retrieval-Augmented Generation (RAG).

Features:
- Real-time fraud prediction
- FAISS-based vector retrieval
- Explainable AI outputs
- FastAPI backend + Gradio UI

Project Structure:
rag-fraud-detection-system/
  api/
  models/
  pipelines/
  ui/
  docs/

Sample Results:
- [RAG Output](rag-fraud-detection-system/docs/rag.pdf)
- [Fraud Case](rag-fraud-detection-system/docs/fraud.pdf)
- [Genuine Case](rag-fraud-detection-system/docs/genuine.pdf)

How to Run:
uvicorn main:app --reload
python ui/app.py
