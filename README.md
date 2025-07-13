# AI-RAG-Assistant-using-LangChain-Final-Project-IBM-GenAI-Capstone-

Overview
This project demonstrates how to build an AI-powered QA Bot using LangChain and open-source LLM tools. It's part of the IBM Generative AI Applications course, specifically targeting RAG (Retrieval-Augmented Generation) pipelines to answer questions based on uploaded documents.

Objective
To create a PDF Question Answering assistant that can:
Load a PDF file
Split the document into manageable text chunks
Convert those chunks into embeddings using Hugging Face models
Store them in a vector database (ChromaDB)
Use a retriever and LLM to answer questions based on the content
Provide a user-friendly interface using Gradio

Features
PDF Loader using PyPDFLoader
Text Splitter for chunking large content
Embeddings generated using HuggingFace’s all-MiniLM-L6-v2 model
Vector Store powered by Chroma
Retriever wrapped inside LangChain’s RetrievalQA
Interactive Web Interface using Gradio with tabs:- Upload PDF and Ask a question

Technologies Used
LangChain
HuggingFace Embeddings
Gradio
ChromaDB
PyPDF2
Transformers
Python 3.x

Outcome
A fully functional and local AI chatbot that can process PDFs and answer user questions based on document content — powered entirely by open-source models, without needing paid APIs.

