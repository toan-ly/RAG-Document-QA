# RAG (Retrieval Augmented Generation) Document QA Chatbot
This project demonstrates the implementation of a Retrieval-Augmented Generation (RAG) system, integrating various libraries and tools to create an efficient and effective chatbot. The system uses a combination of document retrieval and language generation to provide accurate and contextually relevant answers to user queries.


## Installation

To run this project, you need to have Python installed. Follow the steps below to set up the environment and install the required dependencies:
1. Clone this repository:
```bash
git clone https://github.com/toan-ly/RAG-Document-QA.git
cd RAG-Document-QA
```
2. Install the required libraries:
```bash
pip install -r requirements.txt
```

## Usage
### Running the RAG Program
- Open `main.ipynb` on Google Colab, make sure GPU is enabled
- Upload PDF document
- Enter questions related to the document
- The system will process the document, build the vector database, initialize the language model, and answer a predefined question

### Authenticating using Ngrok
To expose the application to the internet using `ngrok`, follow these steps:
1. Create an account on [ngrok](https://ngrok.com/)
2. Authenticate your ngrok account:
```bash
ngrok config add-authtoken YOUR_NGROK_AUTHTOKEN
```

### Running the Chat Interface
To start the chat interface, use the following command:
```bash
chainlit run app.py
```


