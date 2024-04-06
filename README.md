# audio-newsapi-chatbot

## Simple Streamlit app demonstrating LLM interaction with an API

This is a simple application built using OpenAI Apis, streamlit and LangChain,  the app utilizes the `APIChain` component from LangChain to make external API calls and retrieve data from third-party services.

## Prerequisites

Before running this app, make sure you have the following installed:

- Python (version 3.10 or higher)
- Poetry (dependency management tool)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/ai-malaysia/audio-newsapi-chatbot.git

2. Navigate to the project directory:
cd langchain-api-app

3. Install the dependencies using Poetry:
poetry install

4. Usage
stream run news_search_audio.py

Make sure to enter your own OpenAI_API and New_sAPI keys in news_search_audio
os.environ["OPENAI_API_KEY"] = "sk-"
os.environ['NEWS_API_KEY'] = "="

