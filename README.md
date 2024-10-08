# RAG Q&A Conversation With PDF Including Chat History

## Overview
This project enables users to upload PDFs and interact with the content via a chatbot interface, utilizing the Groq API and Hugging Face Embeddings for semantic search and question-answering. It includes chat history awareness to provide contextually relevant responses based on past interactions.

## Features
- Upload multiple PDF files.
- Chat with the content of the uploaded PDFs.
- Statefully manage chat history across sessions.
- Uses Groq API for processing and answering user queries.
- Retrieves answers based on the content of uploaded PDFs using embeddings and semantic search.

## Requirements
- `streamlit`
- `langchain`
- `langchain_chroma`
- `langchain_community`
- `langchain_core`
- `langchain_groq`
- `langchain_huggingface`
- `langchain_text_splitters`
- `python-dotenv`

## Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Ujjwal6710/Medical-LLM-Chatbot.git
cd Medical-LLM-Chatbot
```

### 2. Create a .env File
Create a .env file in the root directory and copy the following lines:
```bash
GROQ_API_KEY = "<groqapi-key>"
HF_TOKEN = "<hf-token>"
```

### 3. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  
```

### 4. Install Required Packages
```bash
pip install -r requirements.txt
```

### 5. Run the Application
```bash
streamlit run main.py
```

## Usage
- Once the app is running, open it in your browser.
- Enter the session ID and upload one or more PDF files.
- Type your questions in the text box to interact with the chatbot.
- The app will process your queries and respond with answers based on the content of the PDFs.


## Contributing

1. **Fork the repository** on GitHub.
2. **Create a new branch** (`git checkout -b feature/YourFeature`).
3. **Make your changes** and commit (`git commit -am 'Add new feature'`).
4. **Push to the branch** (`git push origin feature/YourFeature`).
5. **Create a new Pull Request**.
