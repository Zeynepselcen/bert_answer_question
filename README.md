# BERT Question Answering Application

This project implements a **Question Answering** system using a pre-trained **BERT model**. It allows users to input a context and a question, and the system will provide an answer based on the context provided.

## Features
- **Contextual Question Answering**: Users can input any text (context) and ask a question related to it. The system uses the **BERT model** fine-tuned on the **SQuAD** dataset to provide the most accurate answer.
- **Desktop Interface**: The application uses **Tkinter** to create a simple GUI for local use.

## Technologies Used
- **BERT (Bidirectional Encoder Representations from Transformers)**: A pre-trained model for NLP tasks.
- **Python**: The backend for processing the question and context with BERT.
- **Tkinter**: A standard GUI library for creating desktop applications in Python.
- **Torch**: A deep learning framework used for running the BERT model.
- **Hugging Face Transformers**: The library to load the pre-trained BERT model.
