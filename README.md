# Multi-modal RAG Chatbot

This is a Streamlit application that implements a RAG chatbot using Langchain and OpenAI's api. The chatbot is capable of answering questions based on pre-loaded documents of different formats such as txt, pdf and json. Furthermore it also has speech to text functionality for users inorder to voice command the chatbot.

## Setup

* Clone the repository
* Install the required dependencies:
``pip install -r requirements.txt``
* Obtain an OpenAI API token and save it as a secret in .streamlit folder under secrets.toml file
``OPENAI_API_KEY = "xxx"``
* Prepare your data directory (`./data/`) containing text, PDF, or JSON files.
* Run the Streamlit application:
``streamlit run main.py``

## Technologies and Models used
* ``llm model = gpt-3.5-turbo``
* ``Embedding model = text-embedding-3-large``
* ``Vector database = Chromadb``
* ``Voice transcription = Whisper-1``
