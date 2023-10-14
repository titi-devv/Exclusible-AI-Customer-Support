# 🧑‍💻 AI Customer Support Chatbot

This repository contains code for an AI Customer Support Chatbot. The chatbot is designed to answer user questions based on a set of training data, web scraping, and predefined templates. It utilizes language models and embeddings to provide informative responses.

## Table of Contents

- [Installation](#installation)
- [Creating Data](#creating-data)
- [Creating Language Model (LLM)](#creating-llm-model)
- [Chunks and Embeddings](#chunks-and-embeddings)
- [ChatBot](#chatbot)
- [Get All URLs on a Website](#get-all-urls-on-a-website)
- [Usage](#usage)

## Installation

To use this chatbot, you need to install the required Python packages and dependencies. You can do this by running the following commands:

```bash
!nvidia-smi
!pip install tldextract
!pip install sentence_transformers
!pip install langchain==0.0.228
!pip install chromadb==0.3.26
!pip install sentence_transformer
!pip install auto-gptq==0.2.2
!pip install einops==0.6.1
!pip install unstructured==0.8.0
!pip install transformers
!pip install torch==2.0.1
```

After installing the necessary packages, you can proceed to use the chatbot.

## Creating Data

Before using this conversational AI chatbot, you need to create or gather training data and specify URLs for web scraping. The training data and URLs are essential for the chatbot to provide informative responses.

### Training Data

Training data consists of pairs of questions and answers, and it serves as the foundation for the chatbot's knowledge. To create training data, follow these steps:

1. Define a set of questions that users might ask.
2. Craft informative answers to those questions.

Example training data entries are provided in the code to demonstrate the format. You can add more questions and answers as needed to build a comprehensive knowledge base.

### URLs for Web Scraping

In addition to training data, you can specify URLs for web scraping to gather information from websites. The chatbot can extract data from web pages to enhance its responses.

To specify URLs for web scraping:

1. Create a list of URLs from which you want to collect data.
2. The provided code demonstrates how to extract URLs from a website for web scraping purposes.

Make sure to provide valid URLs that contain relevant information for your chatbot's domain.

## Creating Language Model (LLM)

The Language Model (LLM) is at the core of the chatbot and is responsible for generating responses.

The LLM is created and configured in the provided code. It takes user input and generates responses based on the training data, web scraping, and predefined templates.

## Chunks and Embeddings

The chatbot uses text chunks and embeddings to process and analyze data efficiently. These components play a crucial role in understanding and responding to user queries.

Text chunks are segments of text, and embeddings represent the text's features. This combination allows the chatbot to search for relevant information and provide informative responses.

## ChatBot

The ChatBot class handles user interactions, response generation, and conversation management. 

You can interact with the chatbot by providing input in a conversational manner, and it will generate responses based on its knowledge and training data.

## Get All URLs on a Website

A utility function is provided to extract all URLs from a specified website. This function is used to collect URLs for web scraping and data retrieval. It allows you to retrieve information from web pages and enrich the chatbot's knowledge.

## Usage

To use the chatbot, run the provided code, and then interact with it by asking questions or providing input. The chatbot will process your queries and provide responses based on the training data, web scraping, and predefined templates.

Feel free to have a conversation with the chatbot and see how it performs. You can ask questions and evaluate its responses to gauge its effectiveness.


