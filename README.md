<<<<<<< HEAD
## 🔄 Dynamic Knowledge Base

The Medical AI Assistant uses a dynamic knowledge-base system that allows new medical information to be incorporated into the chatbot over time without retraining the complete machine-learning model.

### Workflow

New Medical Information
        ↓
new_questions.csv
        ↓
scheduler.py
        ↓
knowledge_updater.py
        ↓
Duplicate Detection
        ↓
Sentence Embeddings
        ↓
ChromaDB Vector Database
        ↓
Semantic Search
        ↓
Dynamic Medical Chatbot
        ↓
Updated Medical Response

### Components

- `new_questions.csv` — Stores newly added medical question-answer pairs.
- `knowledge_updater.py` — Reads new information and adds it to the vector database.
- `scheduler.py` — Periodically checks for new medical information.
- ChromaDB — Stores medical knowledge as vector embeddings.
- `dynamic_chatbot.py` — Performs semantic search and retrieves relevant answers.
- `app.py` — Provides the Streamlit user interface.

### Duplicate Prevention

The system checks whether a question already exists in the vector database. Existing questions are skipped, preventing duplicate knowledge from being added.

### Testing Result

A new question was added:

**Question:** What is migraine?

The system successfully:

1. Detected the new question.
2. Added it to the vector database.
3. Increased the total document count.
4. Retrieved the information through the chatbot.
5. Returned the correct answer to the user.

### Example Result

**User Question:**

What is migraine?

**Chatbot Answer:**

Migraine is a neurological condition that can cause severe headache and other symptoms.

### Outcome

The dynamic knowledge-base system successfully enables the chatbot to incorporate new medical information over time without requiring complete model retraining.
=======
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
>>>>>>> e7a5b8b9fdb1af5faa1cef490e63a1e5e3fc5fad
Task 2 – Medical Q&A Chatbot
✓ MedQuAD Dataset
✓ TF-IDF Retrieval
✓ Medical Entity Recognition
✓ Streamlit Interface

Task 3 – Dynamic Knowledge Base
✓ Extends Task 2
✓ Automatic Knowledge Updates
✓ Scheduler
✓ Vector Database Update
✓ New Questions Added Without Retraining
