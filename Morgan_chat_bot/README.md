# Morgan State University Chatbot
This project hosts a specialized chatbot designed for Morgan State University students, particularly those with questions related to computer science, such as administration, class registration, departmental inquiries, and more. Leveraging OpenAI's API and Langchain, this chatbot can read and interpret data, providing tailored responses to various student queries.

## Overview
The chatbot integrates cutting-edge technologies, including OpenAI's API and Langchain, to access and process a database of potential questions students might ask. The data used by the chatbot is stored in the data folder. Our goal is to provide a seamless and interactive experience for Morgan State students seeking information about their computer science program and related administrative processes.

## Installation
Before you start, ensure you have Python installed on your system. 
Follow these steps to set up the chatbot:

### Install Required Packages:

pip install langchain, 
pip install openai 
pip install chromadb 
pip install tiktoken 
pip install unstructured 
pip install flask
pip install selenium

## API Key Configuration:

Obtain your OpenAI API key from OpenAI API Key Portal.
Modify the constants.py file to include your OpenAI API key.

## Data Preparation:

The custom data is located in data/data.txt file. This data is relevant to the queries expected from Morgan State University students.
Usage

# To use the chatbot:

Start the Server:

Run the chatgpt.py file.
python chatgpt.py
This will start a local server.

# Access the Chatbot:

Open your web browser and navigate to localhost:5000.
Interact with the chatbot by typing in your queries.

## Features
Custom Database: Tailored to address specific queries from Morgan State University's computer science students.
OpenAI Integration: Utilizes advanced AI models for accurate and context-aware responses.
User-Friendly Interface: Simple and intuitive web interface for easy interaction.

# Screenshots
Here, include screenshots demonstrating the setup process, the running chatbot interface, and examples of interactions with the chatbot.

![How the program works](C:\Users\Mutho\Downloads\Morgan_chat_bot\Morgan_chat_bot\img\1.png)
![How the program works](C:\Users\Mutho\Downloads\Morgan_chat_bot\Morgan_chat_bot\img\2.png)


# Contributing
Contributions to this project are welcome. Please follow the standard fork-and-pull request workflow. 