# 🤖 RAG Chatbot
RAG Chatbot is a minimal, plug-and-play Retrieval-Augmented Generation (RAG) framework that lets you chat with content scraped from websites or loaded from PDFs. Powered by LLMs like Groq and Gemini.

✨ Features
🌐 Web scraping with LangChain's WebBaseLoader

📄 PDF ingestion using PyPDF

🧠 Smart context retrieval via ChromaDB

🤖 Answers powered by Groq or Gemini LLMs

💻 Notebook-ready pipeline

🖥️ Streamlit app for interactive usage

🛠️ Requirements
🐍 Python 3.8+

📦 pip

📓 Jupyter Notebook (optional)

🔐 API keys for:

Groq

Google Gemini

📦 Installation
🚀 Clone the repo

bash
Copy
Edit
git clone https://github.com/yourusername/rag-chatbot.git
cd rag-chatbot
🧪 Create & activate virtual environment

bash
Copy
Edit
python -m venv rag
# On Windows:
rag\Scripts\activate
# On Unix or MacOS:
source rag/bin/activate
📥 Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
🔐 Environment Variables
Create a .env file in the project root:

env
Copy
Edit
GROQ_API_KEY=your-groq-api-key
GOOGLE_API_KEY=your-gemini-api-key
💡 Use .env for safe and flexible key management.

🚀 Running the Project
📓 Run via Jupyter Notebook
bash
Copy
Edit
jupyter notebook RAG_CHATBOT.ipynb

💡 Usage
🧾 Load data from a URL or PDF

❓ Ask natural language questions

📚 RAG retrieves relevant context

🤖 LLM generates intelligent, context-aware answers

