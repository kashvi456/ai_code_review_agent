# AI Code Review Agent

An AI powered command-line code review agent built with Python, Langchain and OpenAI's GPT-4o that analyzes source code for bugs, security risks and style compliance.

## Tech Stack:
**Language**: Python 3.11

**Framework**: LangChain

**LLM Integration**: Langchain OpenAI(GPT-4o)

**Environment Management**: python-dotenv

**CLI Utilities**: python argparse

## Setup Guide

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/ai_code_review_agent.git
cd ai_code_review_agent
```

### 2. Set Up Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a .env file in the root directory and add your OpenAI API key:

```bash
OPENAI_API_KEY=your_openai_api_key_here
```

## Run

```bash
# To review a file
python agent.py --file path/to/your/code.py

# To review inline code
python agent.py --code "def divide(a, b): return a / b"
```
