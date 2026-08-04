# 🏥 Medical Q&A Chatbot with Dynamic Knowledge Base

A Medical Question Answering chatbot built using **Python, Streamlit, ChromaDB, TF-IDF Retrieval, and the MedQuAD Dataset**. The chatbot supports **dynamic knowledge base expansion**, allowing new medical information to be added automatically without retraining the underlying retrieval model.

---

## 🚀 Features

- 🏥 Medical Question Answering
- 📚 MedQuAD Dataset Integration
- 🔍 TF-IDF Retrieval
- 🧬 Medical Entity Recognition
- 🗂 ChromaDB Vector Database
- 🔄 Dynamic Knowledge Base Updates
- ⏰ Automatic Scheduler
- 🚫 Duplicate Entry Detection
- 📈 Semantic Search
- 🎨 Streamlit Web Interface

---

## 🛠 Technologies Used

- Python
- Streamlit
- ChromaDB
- Scikit-learn
- Pandas
- spaCy
- Sentence Transformers
- TF-IDF Vectorizer

---

## 📂 Project Structure

```
Medical-QA-Chatbot-Dynamic-Knowledge-Base/
│
├── app.py
├── dynamic_chatbot.py
├── knowledge_updater.py
├── scheduler.py
├── entity_recognition.py
├── new_questions.csv
├── requirements.txt
├── README.md
├── chroma_db/
└── data/
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Prathwikdevadiga15/Medical-QA-Chatbot-Dynamic-Knowledge-Base.git
```

Move into the project directory

```bash
cd Medical-QA-Chatbot-Dynamic-Knowledge-Base
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 📖 How It Works

1. User asks a medical question.
2. The chatbot searches the MedQuAD knowledge base.
3. Medical entities are extracted from the query.
4. If new medical data exists, the scheduler updates the ChromaDB vector database.
5. Duplicate entries are ignored.
6. Semantic search retrieves the most relevant answer.
7. The answer is displayed in the Streamlit interface.

---

## 🎯 Assignment Objectives Achieved

- ✅ Medical Question Answering
- ✅ MedQuAD Dataset
- ✅ TF-IDF Retrieval
- ✅ Medical Entity Recognition
- ✅ Dynamic Knowledge Base Expansion
- ✅ Automatic Knowledge Updates
- ✅ Scheduler Integration
- ✅ Vector Database
- ✅ No Model Retraining Required
- ✅ Interactive Streamlit Interface

---

## 📸 Example

**Question**

What are the symptoms of diabetes?

**Answer**

Common symptoms include increased thirst, frequent urination, fatigue, blurred vision, unexplained weight loss, and slow wound healing.

---

## 🔮 Future Improvements

- Integration with latest medical publications
- LLM-powered answer generation
- Medical document upload support
- Multi-language support
- Voice interaction

---

## 👨‍💻 Author

**Prathwik H Devadiga**

GitHub: https://github.com/Prathwikdevadiga15

---

⭐ If you found this project useful, please consider giving it a star.
