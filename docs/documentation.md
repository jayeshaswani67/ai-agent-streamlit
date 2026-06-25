# AI Agent Documentation

## Overview

This project is a conversational AI agent built with Streamlit and Groq.

## Architecture

User
 ↓
Streamlit UI
 ↓
Groq API
 ↓
Llama Model
 ↓
Response

## Components

### Streamlit

Provides frontend UI.

### Groq API

Processes prompts and generates responses.

### Session State

Stores conversation history.

## Workflow

1. User enters prompt.
2. Prompt stored in session.
3. Request sent to Groq.
4. LLM generates answer.
5. Response displayed.

## Security

API keys stored in .env file.

Never commit:

```env
GROQ_API_KEY=...
```

to GitHub.

## Future Enhancements

- Agent Memory
- Tool Calling
- Database Storage
- Authentication
- PDF Reader
- Web Search