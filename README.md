# generative-ai-langchain-projects
Hands-on Generative AI projects using Python, LangChain, Gemini, Streamlit and LangSmith, covering Prompt Engineering, LLM pipelines, Few-Shot Prompting, Output Parsers, Translation and AI chatbot observability.
# 🚀 Generative AI & LangChain Projects
This repository contains two practical projects focused on Prompt Engineering, LLM application development, AI chatbot development, and LLM observability.

## 📌 Projects

### 1. Prompt Engineering with LangChain

Explored different Prompt Engineering techniques using LangChain, including:

- PromptTemplate
- ChatPromptTemplate
- Output Parsers
- LLM Chains
- Few-Shot Prompting
- Few-Shot Chat Prompting
- Language Translation
- Structured Prompting
- LangChain Expression Language (LCEL)

This project helped me understand how structured prompts and examples can improve the quality, consistency, and control of LLM responses.

### 2. Gemini AI Chatbot with LangChain, Streamlit & LangSmith

Built an interactive Gemini-powered AI chatbot using LangChain and Streamlit.

The application allows users to enter questions and receive responses from the Gemini model through an LCEL pipeline.

Application Pipeline:

User Question
      ↓
Prompt
      ↓
Gemini LLM
      ↓
Output Parser
      ↓
Final Response

The LangChain pipeline is:

chain = prompt | llm | output_parser

## 📊 LangSmith Observability

LangSmith is integrated into the chatbot project for LLM observability, tracing, and monitoring.

It helps track and analyze:

- LLM runs
- Execution traces
- Prompt execution
- Response generation
- Application flow
- Performance
- Debugging information

The LangSmith dashboard provides visibility into how requests move through the LLM application.

## 🛠️ Technologies Used

- Python
- LangChain
- Gemini
- Streamlit
- LangSmith
- Jupyter Notebook
- LCEL
- Generative AI
- Large Language Models (LLMs)

## 📂 Project Structure

generative-ai-langchain-projects/
│
├── PromptEngineering.ipynb
├── geminilangsmithllmopscode.py
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md

## ⚙️ Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/generative-ai-langchain-projects.git

cd generative-ai-langchain-projects

Install the required dependencies:

pip install -r requirements.txt

## 🔑 API Key Configuration

Create a .env file in the root directory.

GOOGLE_API_KEY=your_google_api_key_here
LANGCHAIN_API_KEY=your_langsmith_api_key_here
LANGCHAIN_TRACING_V2=true

Never upload your real API keys to GitHub.

## ▶️ Running Project 1

Open PromptEngineering.ipynb using Jupyter Notebook, JupyterLab, or VS Code.

## ▶️ Running Project 2

Run the Streamlit application:

streamlit run geminilangsmithllmopscode.py

## 🎯 Key Learning Outcomes

Through these projects, I gained practical experience in:

- Generative AI
- Prompt Engineering
- LangChain
- Gemini model integration
- LCEL pipelines
- Few-Shot Prompting
- Output Parsing
- Language Translation
- Streamlit application development
- LLM observability
- LangSmith tracing
- LLM monitoring
- API key management
- AI application debugging

## 🚀 Future Improvements

- Add conversational memory
- Add chat history
- Improve chatbot UI/UX
- Add document-based question answering
- Add advanced LangSmith evaluations
- Add multiple LLM providers
- Deploy the chatbot

## 👨‍💻 Author

T pavan kumar


## 🔖 Topics

generative-ai
langchain
gemini
langsmith
prompt-engineering
python
streamlit
llm
machine-learning
artificial-intelligence


requirements.txt

streamlit
langchain
langchain-core
langchain-google-genai
langchain-openai
langsmith
python-dotenv
jupyter


.env.example

GOOGLE_API_KEY=your_google_api_key_here
LANGCHAIN_API_KEY=your_langsmith_api_key_here
LANGCHAIN_TRACING_V2=true


.gitignore

.env
__pycache__/
*.pyc
.venv/
venv/
.ipynb_checkpoints/


