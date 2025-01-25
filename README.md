# DeepSeek Chatbot

A Streamlit-based chat interface that uses the DeepSeek API to provide conversational AI capabilities.

## Features

- Interactive chat interface
- Conversation history during session
- Easy-to-use sidebar guide
- Reset chat functionality

## Prerequisites

- Python 3.8 or higher
- pipenv

## Installation

1. Clone the repository
2. Install dependencies using pipenv:
```bash
pipenv install
```

## Configuration

1. Create a `.streamlit/secrets.toml` file with your DeepSeek API key:
```toml
api_key = "your-api-key-here"
```

## Running the Application

Run the application using pipenv:
```bash
streamlit run app.py
```

## Usage

1. Type your message in the chat input at the bottom
2. View the chatbot's response
3. Continue the conversation with follow-up questions
4. Use the reset button in the sidebar to start a fresh chat

## Development

- Python 3.8+
- Streamlit 1.29.0+
- OpenAI API client 1.6.1+


## Error Handling

- API errors are caught and displayed to the user
- Application errors are logged with timestamps
- User-friendly error messages
