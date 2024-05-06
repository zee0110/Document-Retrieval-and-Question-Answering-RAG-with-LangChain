# Document-Retrieval-and-Question-Answering-RAG-with-LangChain

### README

#### Document Retrieval and Question Answering with LangChain

This code demonstrates a document retrieval and question-answering system using LangChain, a library for building and chaining Natural Language Processing (NLP) components. It leverages document loaders, text splitters, embeddings, vector stores, transformers, and pipelines to efficiently retrieve relevant documents and generate answers to user questions.

#### Prerequisites

Ensure you have Python installed on your system along with the necessary libraries:
- langchain
- torch
- transformers
- sentence-transformers
- datasets
- faiss-cpu

You can install the required libraries using pip:

```
pip install -q langchain torch transformers sentence-transformers datasets faiss-cpu
```

#### Usage

1. Install the required libraries.
2. Clone the repository or download the code files.
3. Run the code using a Python interpreter.
4. The code loads a dataset and splits its text into documents.
5. It then builds embeddings for the documents and creates a FAISS index for efficient retrieval.
6. Users can input questions, and the system retrieves relevant documents based on the queries.
7. It then generates answers to the questions using a question-answering model.
8. The generated answers are displayed to the user.
9. Users can continue to input questions until they decide to exit the system.

#### Features

- Utilizes LangChain library for document retrieval and question answering.
- Implements efficient document retrieval using FAISS (Facebook AI Similarity Search).
- Uses pre-trained embeddings and transformers models for encoding and question answering.
- Provides an interactive interface for users to input questions and receive answers.

