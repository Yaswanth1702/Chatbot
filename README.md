# Robo: A Simple Python Chatbot
## Overview
Robo is a basic rule-based chatbot built using Python and the Natural Language Toolkit (NLTK). This chatbot can respond to user queries by matching greetings and generating responses based on text similarity from a provided corpus. Robo is a great starting point for those interested in building chatbots and exploring natural language processing.

## Features
- **Greeting Recognition**: Robo can recognize and respond to various greetings.
- **Text-Based Response Generation**: It uses TF-IDF (Term Frequency-Inverse Document Frequency) to find the most relevant response from a provided text corpus.
- **Simple Interaction**: Users can interact with Robo until they choose to exit by typing "bye".

### Prerequisites

Ensure you have Python installed on your machine. You'll also need to install the following Python libraries:

- `numpy`
- `scikit-learn`
- `nltk`

### Setup

1. **Prepare the Corpus**:
   
   Include a text file named `chatbot.txt` in the repository root. This file should contain the text corpus Robo will use to generate responses.

2. **Run the Chatbot**:

   Execute the script to start interacting with Robo:

   ```bash
   python robo_chatbot.py
   ```

3. **Interacting with Robo**:

   - Robo will greet you and wait for your input.
   - Type a greeting (e.g., "hello"), and Robo will respond.
   - Ask a question or make a statement related to the corpus, and Robo will try to generate a relevant response.
   - Type "bye" to end the conversation.
