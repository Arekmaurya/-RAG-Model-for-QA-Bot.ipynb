# -RAG-Model-for-QA-Bot.ipynb

This repository implements a Question-Answering (QA) bot using a Retrieval-Augmented Generation (RAG) model, along with alternatives like the Flan-T5 model from Hugging Face. The bot allows for real-time question answering by retrieving relevant information from documents and generating natural language responses.

Features
Retrieval-Augmented Generation (RAG): Combines document retrieval with generative transformers to provide accurate and contextually relevant answers.
Google Flan-T5 Integration: Option to use Google’s Flan-T5 XL for generating responses.
PDF Context Loading: Supports loading documents from PDF files and uses them as a knowledge base for answering queries.
Context Truncation: Ensures context length is within the model's limits.
Embedding-Based Retrieval: Uses Sentence-BERT for embedding-based document similarity and retrieval.
