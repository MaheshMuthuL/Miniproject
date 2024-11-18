## Title of the Project
*AI-Based Law Inquiry Chatbot*

This project is an AI-powered chatbot designed to answer queries related to legal topics, particularly focusing on the Indian Penal Code (IPC). The chatbot leverages the Llama model and FAISS vector store to implement a question-answering (QA) system. It processes legal PDF documents to generate embeddings, enabling efficient and accurate retrieval of information in response to user queries. By combining advanced language modeling with vector-based search, the chatbot ensures precise and context-aware answers tailored to users' legal inquiries.

## About
This project is an advanced AI-driven chatbot designed to address legal inquiries, with a specific focus on providing accurate and context-aware responses based on the Indian Penal Code (IPC). It adapts a framework originally developed for a medical chatbot and tailors it to the legal domain.

## Features
* Domain-Specific Expertise: Unlike general-purpose chatbots, this system is specialized in the legal domain, making it an ideal tool for law students, legal professionals, or individuals seeking clarity on IPC-related matters.
* Real-Time Response: Provides instant answers to user queries, leveraging the power of embeddings and vector search for high-speed performance.
* Expandable Knowledge Base: The chatbot can be updated with additional legal documents or amendments, ensuring it remains relevant over time.

## Requirements
* Operating System: Requires a 64-bit OS (Windows 10, macOS, or Ubuntu) for compatibility with deep learning frameworks and libraries.
* Development Environment: Python 3.8 or later is necessary for coding and executing the chatbot system.
* Deep Learning Framework: Hugging Face's transformers library is used for integrating the Llama model for embeddings and response generation.
* Vector Search Library: FAISS (Facebook AI Similarity Search) is required for implementing the vector store and similarity search.
* PDF Processing Libraries: Libraries like PyPDF2 or pdfplumber are essential for extracting text from legal PDF documents.
* Frontend Development: Use Streamlit or Gradio to create a user-friendly interface for interacting with the chatbot.
* Data Processing Tools: Includes pandas and numpy for efficient data management and numerical operations.
* Version Control: Git is recommended for collaborative development and effective code management.
* IDE: Visual Studio Code (VSCode) or PyCharm can be used as the Integrated Development Environment for coding and debugging.
* Pre-trained Model: Llama model (downloaded from Hugging Face or another trusted source) is required for embedding generation and inference.
* Hardware Requirements:
   * Minimum 8 GB RAM (16 GB recommended for smooth performance).
* Additional Dependencies: Includes transformers, faiss-cpu/faiss-gpu, sentence-transformers, pandas, streamlit, and scikit-learn.

  
## Disclaimer

As of now, this repository contains only law-related content. Users are encouraged to modify and customize the content as needed. If you remove or alter the existing PDF documents, you are free to provide your respective PDF contents to tailor the application to your specific requirements.

## Overview
The system consists of two main components:
1. Ingest.py: Responsible for loading PDF documents, creating embeddings, and saving them to a FAISS vector store.
2. Model.py: Loads the Llama model, sets up a retrieval QA chain, and processes user queries.

## Installation
You can install the required libraries by running the following command in your Google Colab or local environment:
```
pip install langchain chainlit transformers sentence-transformers faiss-cpu huggingface_hub

```

## Getting Started

To get started with the Llama2 Law Bot, you need to:

Set up your environment and install the required packages as described in the Installation section.

Configure your project by updating the DB_FAISS_PATH variable and any other custom configurations in the code.

Prepare the language model and data as per the Langchain documentation.

Start the bot by running the provided Python script or integrating it into your application.

## Usage

The Llama2 Law Bot can be used for answering law-related queries. To use the bot, you can follow these steps:

1.Start the bot by running your application or using the provided Python script.

2.Send a law-related query to the bot.

3.The bot will provide a response based on the information available in its database.

4.If sources are found, they will be provided alongside the answer.

5.The bot can be customized to return specific information based on the query and context provided.

## Running the Code:

Step 1: Create Vector Store with ingest.py

The first step is to ingest your PDF files and create the FAISS vector store.

To run ingest.py:
```
python ingest.py
```
Step 2: Start the QA Bot with model.py

To run model.py:
```
python model.py
```


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![Screenshot (635)](https://github.com/user-attachments/assets/c09dc11b-f92e-4e28-9b2b-21e6a00a63c8)


#### Output2 - Name of the output
![Screenshot (638)](https://github.com/user-attachments/assets/331457bf-64a2-4c74-9fe9-4abe25440759)



## Results and Impact
The AI-Based Law Inquiry Chatbot enhances accessibility to legal information, empowering users with instant, accurate responses to their legal queries. By leveraging advanced natural language processing and vector search technologies, the project simplifies complex legal texts, making them more understandable and accessible to the general public.

This project demonstrates the potential of AI in revolutionizing legal assistance by providing a fast, reliable, and user-friendly interface for legal research and guidance. It serves as a foundation for future advancements in AI-driven legal tools, contributing to a more informed and legally aware society.

## Articles published / References
1. Neelkumar P. Patel et al., "AI and web-based human-like interactive university chatbot (UNIBOT)", In 3rd international conference on electronics communication and aerospace technology (ICECA), 2019.
2. Ajinkya Huddar et al., "Dexter the College FAQ Chatbot", In International Conference on Convergence to Digital World-Quo Vadis (ICCDW), 2020.
3. K. K. Srinivas, A. Peddi, B. G. S. Srinivas, P. A. H. Vardhini, H. L. P. PrasadandS.K. Choudhary, "Artificial Intelligence Techniques for Chat bot Applications,"2022 International Mobile and Embedded Technology Conference(MECON),Noida, India, 2022





