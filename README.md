# Medical-chatbot
With-LLMs-Langchain-Pinecone-Flask-AWS


# How to run ?

# Steps 1 
clone the repository
'''bash
project repo: https://github.com/palandesainath-git/Medical-chatbot.git
'''

#Steps:2 create the environment
'''bash
conda create -n medibot python=3.10 -y
'''
bash
'''
conda activate medibot
'''
# Steps:3  install the requirements
'''bash
pip install -r requirements.txt
'''

# 🩺 Medical-Chatbot

A complete **AI-powered Medical Chatbot** built with **LLMs, LangChain, Pinecone, Flask & AWS**.  
This chatbot provides empathetic, reliable, and grounded medical information based on retrieved documents.

---

## 🚀 Features
- Retrieval-Augmented Generation (RAG) pipeline using **LangChain**
- Document storage & semantic search with **Pinecone**
- Backend powered by **Flask / FastAPI**
- Frontend: Classic **Chat UI (HTML + CSS)**
- Deployed on **AWS / Render**
- Provides **empathetic, clear, and supportive medical guidance**
- Multi-language support (English + Hindi/Marathi mix)

---

## 📂 Project Structure

Medical-chatbot/
│── app.py                # Flask backend entry point
│── store_index.py         # Script to create Pinecone index
│── helper.py              # Utility functions
│── templates/
│    └── chat.html         # Frontend chat UI
│── static/
│    └── style.css         # Chat UI styling
│── data/                  # Medical PDFs / knowledge base
│── requirements.txt       # Python dependencies
│── README.md              # Project documentation


