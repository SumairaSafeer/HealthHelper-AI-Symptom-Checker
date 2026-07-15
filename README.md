# HealthHelper AI: Intelligent Symptom Checker

**RAG-based AI Symptom Checker using Sentence-Transformers + FAISS + Flan-T5**

**Author:** Sumaira Safeer (FA22-BCE-019)  
**Course:** Artificial Intelligence / Applied Machine Learning  
**Institution:** COMSATS University Islamabad, Attock Campus

---

## 📌 Project Overview

**HealthHelper AI** is a prototype intelligent symptom checker built using a **Retrieval-Augmented Generation (RAG)** pipeline. It retrieves relevant medical knowledge from a curated knowledge base and generates natural language answers to health-related questions using a large language model.

The system was developed in Google Colab and deployed as a live **Streamlit** web application using **ngrok**.

---

## 🛠️ Tech Stack

- **Embeddings**: `sentence-transformers` (`all-MiniLM-L6-v2`)
- **Vector Database**: FAISS (Facebook AI Similarity Search)
- **Generation Model**: `google/flan-t5-base`
- **Frontend**: Streamlit
- **Deployment**: Google Colab + ngrok

---

## ✨ Key Features

- Semantic search over a curated knowledge base of 50+ symptom-to-condition statements
- Retrieval-Augmented Generation (RAG) pipeline
- Clean and interactive Streamlit UI
- Real-time answers with retrieved context shown
- Public deployment via ngrok tunnel

---

## 📁 Repository Contents

| Folder       | Description                                      |
|--------------|--------------------------------------------------|
| `Report/`    | Full project report (DOCX)                       |
| `Code/`      | Full Colab notebook code                         |
| `app.py`     | Clean Streamlit application code                 |
| `requirements.txt` | Python dependencies                         |
| `video/`     | Screen recording of the live app (optional)      |

---

## 🚀 How to Run Locally
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

  3. Run the app:
     ```bash
     streamlit run app.py


## 👩‍🎓 Author

**Sumaira Safeer**  
BS Computer Engineering (Final Year)  
COMSATS University Islamabad, Attock Campus  
[LinkedIn](https://www.linkedin.com/in/sumaira-safeer-948804418/)
