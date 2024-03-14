# Plant Disease Prediction System with CNN

This repository contains code and resources for building a plant disease prediction system using a Convolutional Neural Network (CNN).

## Overview

The project demonstrates the following key steps:

1. **Data Preparation**: Importing data from Kaggle using APIs and environment variables. Handling API credentials securely and downloading the dataset.
   
2. **Data Preprocessing**: Preparing the dataset by normalizing image pixel values and using data augmentation techniques to increase the size of the training dataset and prevent overfitting.
   
3. **Model Development**: Building and training a simple CNN model using TensorFlow. Adding convolutional layers, max-pooling layers, dense layers, and an output layer for classification.
   
4. **Model Evaluation**: Evaluating the model based on loss value and accuracy during the training process. Implementing techniques like early stopping to prevent overfitting.
   
5. **Model Deployment**: Saving the trained model and class indices for future use. 

## Getting Started

To get started with the project:

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/plant-disease-prediction.git
    cd plant-disease-prediction
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. dataset:https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

4. Set up Kaggle API credentials as environment variables.

5. Preprocess the data, train the model, and save it along with the class indices.

6. Utilize the trained model for predicting plant diseases.

## Folder Structure


- **test_images**: 
- **notebooks**: ipynb (Google Collab) used for data exploration and model development and training.
- **main.py**: Source code for running the app using streamlit.

