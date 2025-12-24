# IndustryGPT-LLM-Bot-Using-Pre-Trained-Models-Healthcare-and-Pharmaceuticals
# 🧠 CBSE Mental Health Chatbot

A **Retrieval-Augmented Generation (RAG)** based chatbot that answers mental health–related questions **strictly using the CBSE Mental Health Manual**. This project is designed for **academic use**, student demonstrations, and educational purposes, and runs smoothly on **Google Colab (CPU)**.

---

## 📌 Project Overview

Mental health education is an important part of the CBSE curriculum. This project builds an AI-powered chatbot that:

* Uses the **CBSE Mental Health Manual (PDF)** as its only knowledge source
* Retrieves relevant content using **semantic search (FAISS)**
* Generates accurate, student-friendly answers using a **pre-trained language model**
* Provides an interactive **chat-based interface** using Gradio

The chatbot does **not hallucinate answers** and responds only based on the official CBSE document.

---

## 🏗️ System Architecture

1. **PDF Loader** – Loads the CBSE Mental Health Manual
2. **Text Chunking** – Splits large text into manageable overlapping chunks
3. **Embeddings** – Converts text chunks into vectors using Sentence Transformers
4. **Vector Store (FAISS)** – Enables fast semantic similarity search
5. **Retriever** – Fetches relevant chunks based on user queries
6. **Language Model (FLAN-T5)** – Generates answers grounded in retrieved content
7. **Gradio UI** – Provides a user-friendly chatbot interface

---

## 🛠️ Technologies Used

* **Python 3**
* **LangChain Community** (PDF loading & FAISS integration)
* **HuggingFace Transformers** (FLAN-T5 language model)
* **Sentence-Transformers** (Text embeddings)
* **FAISS** (Vector similarity search)
* **Gradio** (Web-based chatbot interface)
* **Google Colab** (Execution environment)

---

## 📂 Project Structure

```
CBSE-Mental-Health-Chatbot/
│
├── CBSE_MH_Manual.pdf        # CBSE Mental Health Manual (data source)
├── chatbot.ipynb            # Main notebook with complete code
├── README.md                # Project documentation
└── requirements.txt         # (Optional) Required dependencies
```

---

## 🚀 How to Run the Project (Google Colab)

1. Open **Google Colab**
2. Upload the notebook and `CBSE_MH_Manual.pdf`
3. Run the installation cell to install dependencies
4. Restart the runtime (important)
5. Run all cells sequentially
6. Click the **Gradio public link** generated at the end
7. Start asking questions related to mental health

---

## 💬 Sample Questions

* What is mental health?
* What is depression?
* What are the signs of stress?
* How can mental well-being be improved?

---

## ✅ Key Features

* 📘 Answers strictly based on CBSE content
* 🧠 Retrieval-Augmented Generation (RAG)
* 👩‍🎓 Student-friendly explanations
* ⚡ Runs on CPU (no GPU required)
* 🌐 Interactive web interface
* 🧩 Well-structured and explainable code

---

## ⚠️ Disclaimer

This chatbot is **for educational purposes only**. It is not a substitute for professional medical or psychological advice. For serious mental health concerns, users should consult a qualified mental health professional.

---

## 🎓 Academic Relevance

This project demonstrates:

* Practical application of Large Language Models (LLMs)
* Use of semantic search and vector databases
* Prompt engineering for controlled responses
* Responsible AI usage in sensitive domains

It is suitable for **final-year projects**, **AI/ML coursework**, and **demonstrations**.

---

## 🙌 Acknowledgements

* **CBSE** for the Mental Health Manual
* **Hugging Face** for pre-trained models
* **LangChain** and **FAISS** for RAG components
* **Gradio** for the chatbot interface

---

⭐ *If you find this project useful, consider giving the repository a star!*
