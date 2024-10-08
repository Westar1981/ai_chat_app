
# AI Chat App

This repository contains the AI Chat App project.

## Introduction
The AI Chat App is designed to provide intelligent conversational capabilities using advanced AI models.

## Features
- Intelligent conversation handling
- Context-aware responses
- Easy integration with various platforms

## Installation
To install the AI Chat App, follow these steps:
1. Clone the repository: `git clone https://github.com/Westar1981/ai_chat_app.git`
2. Navigate to the project directory: `cd ai_chat_app`
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage
To run the AI Chat App, use the following command:
```
python app.py
```

### AI Model Integration
The AI Chat App uses OpenAI's GPT-3 model to generate responses. Make sure to set your OpenAI API key in the `app.py` file.

### Endpoints
- `GET /`: Returns a welcome message.
- `POST /query`: Handles user queries and returns AI-generated responses.
  - Request body: `{"query": "your question"}`
  - Response: `{"response": "AI response to: your question"}`

### Endpoints
- `GET /`: Returns a welcome message.
- `POST /query`: Handles user queries and returns AI-generated responses.
  - Request body: `{"query": "your question"}`
  - Response: `{"response": "AI response to: your question"}`

## Research and Development Plan
For detailed information on the research and development plan, please refer to the [R&D_Plan.md](./R&D_Plan.md) file.

## Contributing
We welcome contributions to the AI Chat App. Please fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.
