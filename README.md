# CS 4300 (Intro to Artificial Intelligence) Semester Project
UMSL, Spring 2022

The objective of this project was to build an artificial neural network to solve a binary classification problem. All of the project code was written in Python in a 
Google Colab notebook. This project utilized the Tensorflow Keras API for deep learning. The accompanying project report was written in LaTeX using Overleaf.

## Phase 1: Data Analysis & Preparation
In the initial phase of the project, the main task was to select a dataset to use for training and testing the neural network model.  

Tasks:
- Select a dataset
- Visualize the data
- Check the output distribution of the data
- Perform data normalization

## Phase 2: Building a Neural Network Model
The primary task of the next phase was to experiment with training models of various capacities to see what capacity would produce the highest accuracy score on the training data.  

Tasks:
- Build a basic model with 1 layer
- Build several different models that increase number of layers and number of neurons per layer
- Build a model that overfits the training data
- Evaluate each model's performance according to accuracy, loss, F1 score, ROC curve, AUC

## Phase 3: Model Selection & Evaluation
The objective for this phase was to select the model that performed best on the dataset.

Tasks:
- Split the dataset into a training set and validation set
- Build a basic model with 1 layer and evaluate on validation set
- Build several more complex models and evaluate on validation set
- Build a model that overfits the training data and evaluate on validation set
- Build a model with early stopping and model checkpointing and evaluate on validation set
- Plot learning curves
- Evaluate models according to accuracy, precision, recall, F1 score

