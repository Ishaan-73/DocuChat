# DocuChat
DocuChat is a RAG based Chatbot application which uses Streamlit as the framework and LangChain for implementing the pipeline, integrating ChromaDB as the vector database for storing and querying PDF contents, alongside local deployment of Phi3 (LLM) to facilitate responsiveness in serving end-user requests.
## Getting Started

Follow these steps to set up and run the project on your local machine.


### Installation

```sh
## Clone the repository
git clone <repository_url>

##Create the necessary folders
mkdir docs

##Install ollama and then phi3 LLM locally using:
ollama run phi3
----
### Usage

## Start the chatbot application using Streamlit

`streamlit run app.py`
