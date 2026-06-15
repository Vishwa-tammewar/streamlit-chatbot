# Free Mistral API Chatbot

A simple chatbot application built using Streamlit and Mistral AI. Users can enter messages and receive AI-generated responses through an interactive web interface.

## Features

* Simple and clean user interface
* Powered by Mistral AI
* Session-based chat history
* Secure API key management using Streamlit Secrets
* Fast response generation

## Tech Stack

* Python
* Streamlit
* Mistral AI SDK

## Project Structure

```text
.
├── app.py
├── .streamlit
│   └── secrets.toml
├── requirements.txt
└── README.md
```

## Installation

### Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Configuration

Create the following file:

```text
.streamlit/secrets.toml
```

Add your Mistral API key:

```toml
[MISTRAL]
api_key = "your_mistral_api_key"
```

## Running the Application

Start the Streamlit server:

```bash
streamlit run app.py
```

The application will open in your default web browser.

## Usage

1. Enter a message in the input field.
2. Submit the message.
3. The chatbot sends the request to Mistral AI.
4. The generated response is displayed on the screen.
5. Previous messages remain visible during the session.

## Requirements

```text
streamlit
mistralai
```

## License

This project is available under the MIT License.

