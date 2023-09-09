# LangChain Datasheet Bot

## Project Overview

This project utilizes the LangChain library with the RAG (Retrieval-Augmented Generation) technique to provide access to <b> public PDF files of Viavi Solutions website </b> and create a chatbot capable of providing information about their products. The bot takes user prompts and generates responses by querying the LangChain model, including relevant information from Viavi Solutions' PDF documents.
Requirements

#![Demo](https://github.com/vanzei/NitroBOT/blob/main/code/static/gif_chat.gif)


### Before running the project, make sure you have the following dependencies installed:

```bash
    Python 3.11
    Streamlit
    Dotenv
    OpenAI`s GPT-3 model (for LangChain)
    Other Python libraries as required (specified in the code)
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PINECONE_API_KEY`

`PINECONE_ENVIRONMENT_REGION`

`OPENAI_API_KEY`

## Run Locally

Clone the project

```bash
  git clone git@github.com:vanzei/NitroBOT.git
```

Go to the project directory

```bash
  cd NitroBOT
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the flask server

```bash
  streamlit run main.py
```

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.leovanzei.com/projects)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leonardovanzei/)

![](https://app.screencast.com/Jrr4C4ul5TtmA?conversation=hGBPCGspQMqZTeeQwHhs6v)
