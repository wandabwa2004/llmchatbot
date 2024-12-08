# KnowItAll Chatbot 🤖

## Description:  
A smart, feature-rich chatbot built using OpenAI's GPT-4 API and Streamlit. "KnowItAll" can answer questions, generate content, translate text, and even write code. It provides an intuitive interface for users to interact with powerful AI capabilities.

## Features
- **Ask a Question**: Get answers to any question from GPT-4.
- **Generate Content**: Create articles, blog posts, or other creative content.
- **Translate Text**: Translate text into different languages.
- **Write Code**: Generate efficient and readable code snippets for various programming tasks.

## Tech Stack
- **Streamlit**: Frontend framework for building the user interface.
- **OpenAI GPT-4 API**: Backend AI engine for generating responses.
- **Python**: Programming language used for logic and integration.

## Setup Instructions
### Prerequisites
- Python 3.7 or later
- An OpenAI API key (Get yours [here](https://platform.openai.com/signup/)).

## Installation
1. Clone the repository:
```
git clone https://github.com/your-username/knowitall-chatbot.git
cd knowitall-chatbot
```

2.Install the required dependencies:
```
pip install -r requirements.txt
```

3. Run the app:
```
streamlit run app.py
```
The file structure is  as follows :
```
knowitall-chatbot/
├── app.py               # Main Streamlit app
├── utils.py             # Utility functions for API calls and prompt generation
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```
**How to Use**
1. Enter Your OpenAI API Key:
   - Input your OpenAI API key in the sidebar to authenticate.
   - The key is securely stored in the session during your interaction.
2. Select a Feature:
   - Choose from the available features: "Ask a Question", "Generate Content", "Translate Text", or "Write Code."
3. Input Your Prompt:
   - Type your query or request into the input box.
4. Submit:
   - Click the "Submit" button to interact with the GPT-4 model.
5. View Results:
   - See the generated response displayed below the input area. If you've chosen "Write Code," the result is shown in a syntax-highlighted code block.
