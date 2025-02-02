# AI-CHATBOT-WITH-NLP

COMPANY:CODTECH IT SOLUTIONS

NAME:om suresh deshmukh

INTERN ID:CT08KWT

DOMAIN:PYTHON PROGRAMMING

DURATION:4 WEEKS

MENTOR:NELLA SANTOSH

ChatBuddy is a basic rule-based AI chatbot built using the SpaCy NLP library. It matches user inputs to pre-defined responses from a simple knowledge base and demonstrates the use of SpaCy for recognizing named entities in user text.

Features

Provides pre-defined responses based on specific user inputs.

Utilizes SpaCy to process text and extract named entities.

Prints recognized entities and their labels for educational purposes.

How It Works

The chatbot greets the user and waits for input.

If the user's input matches a key in the knowledge base, ChatBuddy responds with the corresponding message.

If no match is found, the chatbot provides a default response.

The chatbot displays named entities identified in the user's input using SpaCy.

Typing bye exits the chatbot.

Knowledge Base

The chatbot responds to the following user inputs:

hello: "Hi there! How can I help you today?"

how are you: "I'm just a program, but I'm doing great! How about you?"

what is your name: "I'm your friendly AI chatbot. You can call me ChatBuddy!"

bye: "Goodbye! Have a great day!"

Any other input returns a default response: "I'm sorry, I didn't understand that. Can you please rephrase?"

Usage Instructions

Prerequisites

Python 3.x

Jupyter Notebook

SpaCy

SpaCy language model en_core_web_sm

Installation

Clone this repository or download the notebook file.

Install the required packages using pip:

pip install spacy notebook

Download the SpaCy language model:

python -m spacy download en_core_web_sm

Running the Chatbot in Jupyter Notebook

Open Jupyter Notebook:

jupyter notebook

Navigate to the location of the notebook file and open it.

Execute each cell sequentially to load the chatbot and interact with it.

Example Interaction

Chatbot: Hello! I'm ChatBuddy. Type 'bye' to exit.
You: Hello
Chatbot: Hi there! How can I help you today?
Entity: Hello, Label: GREETING
You: What is your name?
Chatbot: I'm your friendly AI chatbot. You can call me ChatBuddy!
Entity: name, Label: PERSON
You: bye
Chatbot: Goodbye!

Code Breakdown

Imports: Uses spacy.load("en_core_web_sm") to load the SpaCy language model.

Knowledge Base: A dictionary that maps user inputs to specific chatbot responses.

Entity Recognition: The code uses SpaCy's doc.ents to extract and print named entities.

Response Function (response): Matches user input with keys in the knowledge base.

Chatbot Function (chatbot): Provides the main interaction loop.

Future Enhancements

Expand the knowledge base for more diverse conversations.

Add machine learning models for dynamic response generation.

Improve NLP processing for better intent detection.

#OUTPUT-
![Image](https://github.com/user-attachments/assets/ca24500a-fde4-40be-bd65-c60b7b61ed59)
