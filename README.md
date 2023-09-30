# Kaggle-SQuAD2-Albert-QA

This repository contains the code and resources for a Question-Answering (QA) model based on the ALBERT language model, trained and evaluated on the Stanford Question Answering Dataset (SQuAD) version 2.0. The model is designed to answer questions based on a given context and has been fine-tuned for this specific task.

## Key Features
1. <b>Environment Setup</b>: The code includes the setup for the Python environment, including the installation of necessary libraries and dependencies using pip.
2. <b>Data Preparation</b>: It provides functions for parsing and preparing the SQuAD 2.0 dataset, including reading JSON files and modifying answer contexts for better alignment.
3. <b>Custom Dataset</b>: The code defines a custom dataset class for DataLoader, allowing efficient data loading and processing for training and validation.
4. <b>Model Configuration</b>: It configures the ALBERT model for Question Answering, setting hyperparameters such as learning rate, batch sizes, and number of epochs.
5. <b>Training</b>: The repository includes the training loop for the QA model, along with logging and metrics tracking. It utilizes PyTorch Lightning for streamlined training.
6. <b>Learning Rate Finder</b>: There is code to run a learning rate finder, which helps identify an optimal learning rate for training the model.
7. <b>Model Checkpointing</b>: It implements model checkpointing, saving the best model based on validation loss.
8. <b>Testing</b>: The code includes an example of how to use the trained model to answer questions from a given context.
9. <b>Model Saving</b>: It saves the trained model, tokenizer, and training arguments for future use.
