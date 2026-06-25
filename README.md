# 🤖 AI Agent using Streamlit + Groq

An AI-powered chatbot built with Python, Streamlit, and the Groq API. The application provides real-time conversational responses with chat history support and a clean web interface.

## 🚀 Live Demo

🔗 https://ai-agent-app-i8fgd7fxqmz6wu2ypser37.streamlit.app/

## 📸 Preview

Add screenshots of your application here.

```text
assets/
├── Screenshot(293).png
└── Screenshot(294).png
```

## ✨ Features

* Real-time AI Chat
* Conversation Memory
* Fast Responses using Groq LLMs
* Secure API Key Management
* Responsive Streamlit Interface
* Easy Deployment with Streamlit Cloud

## 🛠️ Tech Stack

* Python
* Streamlit
* Groq API
* python-dotenv

## 📂 Project Structure

```text
ai-agent-streamlit/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── docs/
    └── documentation.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/jayeshaswani67/ai-agent-streamlit.git
cd ai-agent-streamlit
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
```

### Run the Application

```bash
streamlit run app.py
```

The application will be available at:

```text
http://localhost:8501
```

## 🧠 Supported Models

* Llama 3.3 70B Versatile
* Mixtral
* Gemma

## 🔒 Security

* API keys are stored using Streamlit Secrets or environment variables.
* `.env` files are excluded using `.gitignore`.
* Never commit API keys to GitHub.

## 📈 Future Improvements

* Voice-enabled AI Agent
* PDF Document Chat
* Web Search Integration
* RAG (Retrieval-Augmented Generation)
* Multi-Agent System
* User Authentication
* Chat Export Feature

## 👨‍💻 Author

Jayesh

BCA Student | Full Stack Developer | AI Enthusiast

Building projects in AI, Web Development, and Software Engineering.

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.
