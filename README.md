# generative-ai-langchain-projects
Hands-on Generative AI projects using Python, LangChain, Gemini, Streamlit and LangSmith, covering Prompt Engineering, LLM pipelines, Few-Shot Prompting, Output Parsers, Translation and AI chatbot observability.
# 🚀 Generative AI & LangChain Projects

A collection of hands-on **Generative AI projects** developed using **Python, LangChain, Gemini, Streamlit, and LangSmith**.

This repository contains two practical projects focused on **Prompt Engineering, LLM application development, AI chatbot development, and LLM observability**.

---

## 📌 Projects

### 1️⃣ Prompt Engineering with LangChain

The first project focuses on understanding and implementing different **Prompt Engineering techniques using LangChain**.

#### Topics Covered

- PromptTemplate
- ChatPromptTemplate
- Output Parsers
- LLM Chains
- Few-Shot Prompting
- Few-Shot Chat Prompting
- Language Translation
- Structured Prompting
- LCEL

#### Learning Outcomes

This project helped me understand how structured prompts and examples can be used to improve the quality, consistency, and control of LLM responses.

---

### 2️⃣ Gemini AI Chatbot with LangChain, Streamlit & LangSmith

The second project is an interactive **Gemini-powered AI chatbot** built using **LangChain and Streamlit**.

The application allows users to enter questions and receive responses from the Gemini model through a structured LangChain pipeline.

#### 🔄 Application Pipeline

```text
User Question
      ↓
Prompt
      ↓
Gemini LLM
      ↓
Output Parser
      ↓
Final Response

The application uses LangChain Expression Language (LCEL) to connect the different components.

Example:

chain = prompt | llm | output_parser
📊 LangSmith Observability

LangSmith is integrated into the chatbot project for LLM observability and monitoring.

It allows the application to track and analyze:

LLM runs
Execution traces
Prompt execution
Response generation
Application flow
Performance
Debugging information

The LangSmith dashboard provides visibility into how requests move through the LLM application.

User Request
     ↓
LangChain
     ↓
Gemini
     ↓
Output Parser
     ↓
Response
     ↓
LangSmith Trace & Monitoring
🛠️ Technologies Used
Technology	Purpose
Python	Programming Language
LangChain	LLM Application Framework
Gemini	Generative AI Model
Streamlit	Web Application Interface
LangSmith	LLM Tracing & Observability
Jupyter Notebook	Experimentation & Learning
LCEL	LangChain Pipeline Development
📂 Repository Structure
generative-ai-langchain-projects/
│
├── PromptEngineering.ipynb
│
├── geminilangsmithllmopscode.py
│
├── requirements.txt
│
├── .env.example
│
├── .gitignore
│
└── README.md
⚙️ Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/generative-ai-langchain-projects.git

Move into the project directory:

cd generative-ai-langchain-projects

Install the required dependencies:

pip install -r requirements.txt
🔑 API Key Configuration

Create a .env file in the root directory.

GOOGLE_API_KEY=your_google_api_key_here
LANGCHAIN_API_KEY=your_langsmith_api_key_here
LANGCHAIN_TRACING_V2=true
⚠️ Security

Never upload your API keys to GitHub.

The .env file should be included in .gitignore.

Use .env.example as a safe template:

GOOGLE_API_KEY=your_google_api_key_here
LANGCHAIN_API_KEY=your_langsmith_api_key_here
LANGCHAIN_TRACING_V2=true
▶️ Running Project 1

Open:

PromptEngineering.ipynb

Run the notebook using:

Jupyter Notebook
JupyterLab
VS Code
▶️ Running Project 2

Start the Streamlit application:

streamlit run geminilangsmithllmopscode.py

The chatbot will open in your browser.

🎯 Key Learning Outcomes

Through these projects, I gained practical experience in:

Generative AI
Prompt Engineering
LangChain
Gemini model integration
LCEL pipelines
Few-Shot Prompting
Output Parsing
Language Translation
Streamlit application development
LLM observability
LangSmith tracing
LLM monitoring
API key management
AI application debugging
🚀 Future Improvements
Add conversational memory
Add chat history
Improve chatbot UI/UX
Add document-based question answering
Add advanced LangSmith evaluations
Add multiple LLM providers
Deploy the chatbot
👨‍💻 Author

Your Name

🔖 Topics
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

⭐ If you find this project useful, feel free to star the repository!
