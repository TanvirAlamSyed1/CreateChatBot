# ChatGPT-Powered PDF Assistant
## Overview 📄
This project is a web-based PDF assistant powered by Large Language Models (LLMs). It allows you to upload a PDF document and then engage in an interactive chat session to ask questions about its content. The application leverages the power of Langchain and OpenAI to understand your document and provide accurate, context-aware answers.

## How It Works ⚙️
You simply upload a PDF file through the user-friendly Streamlit interface. The application processes the document, extracts the text, and prepares it for an LLM. You can then ask questions in a chat window, and the AI assistant will respond based on the information contained within the uploaded PDF.

## Technology Stack 🛠️
- Backend: Python
- Web Framework: Streamlit
- LLM Orchestration: Langchain
- Language Model: OpenAI API (GPT-3.5/GPT-4)

## Prerequisites 🔑
Before you begin, ensure you have the following:

- Python 3.8+: You can download it from python.org.
- OpenAI API Key: This project requires an API key from OpenAI.
- You must have a funded OpenAI account, as API usage incurs costs. A small starting balance (e.g., $5-$10) is usually sufficient for initial testing.
- To prevent unexpected charges, you can set usage limits and disable auto-recharging in your OpenAI account settings.

## How to Run the Application 🚀
Clone the Repository (Optional):
- If you have git, you can clone the project files.

Bash

git clone <your-repository-url>
cd <repository-directory>
Install Dependencies:
Open your terminal and run the following command to install the necessary Python libraries from the requirements.txt file.

Bash

pip install -r requirements.txt
Set Up Your API Key:
You will need to set your OpenAI API key as an environment variable or directly in the code as instructed within the application's files.

Run the App:
Execute the following command in your terminal. Streamlit will start the application and provide a local URL to open in your web browser.

Bash

streamlit run app.py
