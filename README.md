# 🧠 AI Tutor with RAG and Adaptive Learning

An AI-powered tutoring system that leverages **Retrieval-Augmented Generation (RAG)**, adaptive quizzes, and performance tracking to deliver a personalized learning experience.

---

## 🚀 Features

- ✅ **Retrieval-Augmented Generation (RAG)** – Uses vector databases for accurate AI responses  
- ✅ **AI Chatbot** – Provides subject-specific explanations  
- ✅ **Quiz Generation** – Creates dynamic quizzes from PDFs  
- ✅ **Adaptive Learning System** – Adjusts quiz difficulty based on performance  
- ✅ **Student Performance Dashboard** – Tracks progress and suggests resources  
- ✅ **SQLite Database** – Stores quiz attempts and student progress  
- ✅ **Streamlit UI** – Simple and interactive frontend  

---

## 📂 Project Structure
AI-Tutor/

│── data/ # PDFs & knowledge base

│── assets/ # Logos, icons, images

│── models/ # Vector database & LLM models

│── env/ # Environment files

│── logs/ # System logs

│── app.py # Main Streamlit app

│── login.py # User authentication

│── chat.py # AI chatbot logic

│── quiz.py # Quiz generation

│── dashboard.py # Performance tracking

│── database.py # SQLite operations

│── utils.py # Helper functions

│── styles.css # UI customization

│── README.md # Documentation

│── requirements.txt # Dependencies

│── .gitignore # Ignored files

---

## 🏗️ Installation

### 1️⃣ Clone the Repository
```bash
https://github.com/Mohan96766/ai-tutor-rag-adaptive-learning.git
cd AI-Tutor

2️⃣ Create a Virtual Environment
python -m venv ai_tutor_env
Activate environment:
ai_tutor_env\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Setup Environment Variables
Create a .env file in the root directory and add:
OPENAI_API_KEY=your_openai_api_key
CHROMADB_PATH=data/vector_db

🚀 Running the Application
streamlit run app.py
Open your browser and go to:
http://localhost:8501

🔍 Implemented RAG (Retrieval-Augmented Generation)
✅ 1. Document Ingestion

Extracts content from PDFs, textbooks, and notes for knowledge retrieval.

✅ 2. Vector Database

Uses FAISS / ChromaDB / Pinecone to store and retrieve relevant data.

✅ 3. Context-Aware Responses

Generates accurate answers based on retrieved content.

✅ 4. Quiz Generation

Creates personalized questions using retrieved knowledge.

📢 Deployment
🔹 Push Code to GitHub
git add .
git commit -m "Initial commit"
git push origin main

🔹 Deploy on Streamlit Cloud
1.Go to Streamlit Cloud
2.Connect your GitHub repository
3.Select app.py as the main file
4.Click Deploy 🎉

📚 Future Enhancements
🎤 Speech-to-Text Support
🤖 More LLM Models (Llama 2, GPT-4, Mistral)
📊 Multi-User Progress Tracking

💡 Contributions

Want to improve this project?

1.Fork the repository
2.Make your changes
3.Submit a Pull Request
📄 License

This project is licensed under the MIT License.
