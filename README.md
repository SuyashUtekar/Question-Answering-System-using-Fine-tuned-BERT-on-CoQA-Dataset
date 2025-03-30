# Question Answering System using Fine-tuned BERT on CoQA Dataset

This repository contains the implementation of a **Question Answering (QA) system** using the **BERT model** fine-tuned on the **CoQA dataset**. The goal of the project is to train a conversational QA system capable of answering questions based on the context of a conversation.

## Project Overview

The project utilizes the **CoQA (Conversational Question Answering)** dataset, which is specifically designed to evaluate question answering models on dialogues. It requires the model to handle context over multiple turns of conversation, unlike traditional single-turn QA systems.

In this implementation, a pre-trained **BERT (Bidirectional Encoder Representations from Transformers)** model is fine-tuned on the CoQA dataset to create a system that can understand conversational context and provide accurate answers to questions.

## Features

- **Conversational Context Understanding:** Fine-tuned BERT model capable of understanding multi-turn dialogue for accurate question answering.
- **Data Preprocessing:** Data loading, cleaning, and formatting for training the model.
- **Pipeline Implementation:** A complete pipeline for tokenizing input questions, passing them through the model, and extracting answers.
- **Model Evaluation:** Model performance evaluation based on the CoQA dataset metrics.

## Technologies Used

- **Python**: Programming language used for implementing the solution.
- **BERT (Transformers)**: The pre-trained BERT model fine-tuned for the QA task.
- **Hugging Face's Transformers Library**: For implementing the BERT model and handling tokenization.
- **PyTorch**: Framework used for model training and evaluation.
- **Pandas**: Used for data manipulation and handling the CoQA dataset.
