**AI Interview Chatbot Overview**

AI Interview Chatbot is a Streamlit-based application that uses Large Language Models (OpenAI or Ollama) to generate job-specific interview questions and evaluate candidate responses. The system simulates a real interview experience and provides AI-based feedback.

*Features*

Generates interview questions based on job description
Interactive chat interface
AI-powered response evaluation
Supports OpenAI and Ollama (local models)
Configurable prompts and job roles

*Technologies Used*

Python
Streamlit
OpenAI API / Ollama
Python-dotenv

**Installation
Prerequisites**

Python 3.11+
pip or uv package manager

*Set Up*

git clone <repository-url>
cd interview-bot
pip install -r requirements.txt

Create a .env file and add:

LLM_PROVIDER=openai

OPENAI_API_KEY=your_api_key

OPENAI_MODEL=gpt-4o-mini

Usage

Run the application:

streamlit run chatbot.py

Open browser at:

http://localhost:8501

The chatbot asks interview questions and evaluates responses after completion.

**Project Structure**

interview-bot/
├── chatbot.py
├── config.py
├── utils.py
├── requirements.txt
├── README.md
└── tests/

**Troubleshooting**
Ensure virtual environment is activated
Verify API key in .env
Check model availability
Restart Streamlit if errors occur

**Purpose**

This project demonstrates AI-based interview automation using LLMs and can be extended for recruitment screening or interview practice platforms.
