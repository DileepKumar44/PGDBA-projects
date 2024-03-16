# Machine Learning Project: Risk Classification

## Project Overview

This machine learning project aims to classify risks based on various features. The dataset undergoes preprocessing to handle missing values, convert categorical features into numerical, and split into training and testing sets for model evaluation.

## Data Preprocessing

1. **Reading the Dataset**: Initial step to load the data for processing.
2. **Column Conversion**: Converts specific columns to categorical classes. '0' indicates No, '1' indicates Yes, and '2' indicates no information or missing values.
3. **Target Conversion**: The target feature is binary, with classes 1-3 converted to class 1 (high risk) and classes 4-7 to class 0 (low risk).
4. **Feature Dropping**: Irrelevant columns to the target variable are dropped to improve model accuracy.
5. **Heatmap Plotting**: Analyzes correlation between variables to refine feature selection.
6. **Handling Highly Correlated Features**: Drops features like 'INTUBED' due to high correlation with 'PATIENT_TYPE'.

## Model Building and Evaluation

1. **Separation of Variables**: Dependent and target variables are separated for model training.
2. **Train-Test Split**: The dataset is split into 80% training and 20% testing parts.
3. **Neural Network Architecture**: Defines the structure and layers of the neural network.
4. **Activation and Loss Functions**: Specifics on the activation functions and loss function used for training.
5. **Weight and Bias Updates**: Mechanism for updating the model parameters during training.
6. **Model Training Loop**: Includes forward pass, loss computation, and backpropagation.
7. **Evaluation**: Uses training and test data to evaluate the model's performance and generate classification reports.

## Usage

The project includes functions for data preprocessing, model training, and evaluation. Users can adapt the provided scripts to their datasets or use the project as a template for similar classification tasks.


