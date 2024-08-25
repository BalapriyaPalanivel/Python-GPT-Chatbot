# OpenAI Chatbot

This is a simple Python-based chatbot that uses the OpenAI API to interact with users. The chatbot takes user input, sends it to the OpenAI GPT model, and returns a response.

## Features

- Interact with the GPT-3.5-turbo model.
- Simple command-line interface.
- Continuously chat with the bot until the user decides to quit.

## Prerequisites

- Python 3.7 or higher
- OpenAI Python library

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/openai-chatbot.git
    cd openai-chatbot
    ```

2. **Install required packages**:
    ```bash
    pip install openai
    ```

3. **Set up your OpenAI API key**:
   Replace `"your open-ai-api-key"` in the code with your actual OpenAI API key. You can get your API key from the [OpenAI Platform](https://platform.openai.com/).

## Usage

1. **Run the chatbot**:
    ```bash
    python main.py
    ```

2. **Interact with the chatbot**:
    - Type your message and press `Enter`.
    - To end the conversation, type `quit`, `exit`, or `bye`.

## Example

```bash
You: Hello
Chatbot: Hello! How can I assist you today?

You: What is the capital of France?
Chatbot: The capital of France is Paris.

You: bye
Chatbot: Goodbye! Have a great day!
