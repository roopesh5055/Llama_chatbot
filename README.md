# Langchain Chatbot with LLaMA3

## Overview

This repository contains a simple implementation of a chatbot using LLaMA3 via the LangChain framework. 
The chatbot is designed to respond to user queries based on the prompt template provided. The interface is built using Streamlit, 
making it easy to interact with the chatbot through a web-based UI.

## Features

- **LLaMA3 Integration**: Utilizes the LLaMA3 model from Ollama through LangChain to generate responses.
- **Streamlit Interface**: A clean and interactive UI for chatting with the bot.
- **Customizable Prompts**: Modify the system prompt to adjust the behavior and tone of the chatbot.

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/roopesh5055/Llama_chatbot.git
    cd Llama_chatbot
    ```

2. **Create a Virtual Environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. **Install the Required Packages**:

    Install the dependencies listed in the `requirements.txt` file:

    ```bash
    pip install -r requirements.txt
    ```

4. **Set Up Environment Variables**:

    - Create a `.env` file in the root directory of the project.
    - Add the `LANGCHAIN_API_KEY` to the `.env` file:

    ```bash
    LANGCHAIN_API_KEY=your_api_key_here
    ```

5. **Run the Application**:

    Launch the Streamlit app:

    ```bash
    streamlit run app.py
    ```

6. **Interacting with the Chatbot**:

    - Open the provided local URL in your browser to start interacting with the chatbot.

## Usage

- **Input Field**: Type your query in the input field and press `Enter`.
- **Chat with the Bot**: The bot will respond based on the LLaMA3 model and the prompt template defined in the code.

## File Structure

- **app.py**: The main script to run the Streamlit application.
- **requirements.txt**: Contains the list of Python packages required to run the project.
- **.env**: Environment variables for API keys (not included in the repo, needs to be created by the user).

## Requirements

- Python 3.8 or higher
- Streamlit
- LangChain
- Ollama
- dotenv
