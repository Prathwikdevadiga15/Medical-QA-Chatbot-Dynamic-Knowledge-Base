# 🩺 Dynamic Medical QA Chatbot

An AI-powered medical question-answering chatbot with a dynamically expanding knowledge base.

## 🚀 Features

- 🩺 Medical Question Answering
- 🔄 Dynamic Knowledge Base Updates
- 🧠 Semantic Search using Sentence Transformers
- 🗄️ ChromaDB Vector Database
- ⏰ Automatic Scheduled Updates
- 🔎 Medical Entity Recognition
- 😊 Sentiment Analysis
- 🌐 Streamlit Web Interface
- 🚫 Duplicate Question Detection

## 🏗️ System Architecture

User Question
↓
Streamlit Interface
↓
Medical Question Processing
↓
Semantic Search
↓
ChromaDB Vector Database
↓
Relevant Medical Answer

## 🔄 Dynamic Knowledge Base

New questions can be added to:

datasets/new_questions.csv

The scheduler automatically checks for new questions and adds them to the vector database.

## 🛠️ Technologies Used

- Python
- Streamlit
- ChromaDB
- Sentence Transformers
- spaCy
- TextBlob
- Pandas
- Scikit-learn

## ▶️ How to Run

Install dependencies:

pip install -r requirements.txt

Start the chatbot:

streamlit run app.py

Run the scheduler:

python scheduler.py

## ⚠️ Disclaimer

This chatbot is for educational and informational purposes only.
It is not a replacement for professional medical advice.

## 👨‍💻 Author

Prathwik H Devadiga
