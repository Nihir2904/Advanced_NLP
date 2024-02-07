# Advanced_NLP
contains Sequential methods to solve NLP problems and prerequisites


# 1-Local LLM 🤖

Local LLM is an AI assistant built using a local language model. It uses the book "Surely You're Joking, Mr. Feynman!" as a knowledge source.

## Key Features 🚀

- Locally loaded LLaMA model for privacy and control
- Uses retreival augmented generation technique contextualize the model with some privately owned data
- Trained on "Surely You're Joking, Mr. Feynman!" for more personality 
- Built with LangChain for easy retriever-reader chaining
- Integrated with Chainlit for prototype UI

## Contents 📂

The project contains the following key files:

- `ingest.py`: Scrapes PDF files and indexes them into a vector DB for retrieval  
- `model.py`: Chains the LLaMA model with the vector DB to create a conversational retriever-reader
- `chainlit.md`: Basic Chainlit app for prototyping a chat UI 

## Getting Started 💻

To run the Local LLM assistant:

1. Install requirements
2. Run `ingest.py` to index data
3. Run `model.py` to launch the model 
4. Launch Chainlit to connect to the chatbot UI

See the documentation for more details.

## About the Data 📚

The book "Surely You're Joking, Mr. Feynman!" contains stories and anecdotes from the life of scientist Richard Feynman. Using this entertaining and humorous content helps Local LLM have more fun, interesting conversations.

## Future Plans 🚧

Ideas for improving Local LLM:

- Train on more conversational data
- Experiment with different reader models 
- Build a custom frontend interface
- Package model serving for easy deployment

## Contributions 🤝

Suggestions and pull requests welcome!

Let me know if you have any other questions!
