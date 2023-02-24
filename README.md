
# OpenAI Chatbot Interface

Interact with OpenAI's GPT-3 models in real-time using your OpenAI API. Choose from a selection of their best models, set the temperature and max tokens, and start a conversation. Delete the conversation at any time to start fresh.

# Web App
Click [Here](https://kaludii-openai-chatbot-app-jd0vo6.streamlit.app/ "Here") To View This App Online!

![Image](https://github.com/Kaludii/OpenAI-Chatbot/blob/main/images/OpenAI-Chatbot.png?raw=true)

## Features

-   Interact with OpenAI's models in real-time
-   Choose from a selection of the best models
-   Set the temperature and max tokens
-   Start a conversation and delete it at any time

## Usage

To use the app, input your OpenAI API key in the Configuration sidebar. Then select a model, set the temperature and max tokens, and start a conversation by entering a prompt and clicking on the "Submit" button. The conversation history can be deleted at any time by clicking on the "Delete Conversation" button.

## Technical details

The app uses Streamlit for the user interface and the OpenAI API to access OpenAI's language models. The app supports four models: text-davinci-003, text-curie-001, text-babbage-001, and text-ada-001.

## Requirements

-   Python 3.6 or higher
-   Streamlit
-   Requests

## Installation

1.  Clone the repository:

`git clone https://github.com/Kaludii/OpenAI-Chatbot.git` 

2.  Install the required packages:

`pip install streamlit requests` 

3.  Run the app:

`streamlit run app.py`
