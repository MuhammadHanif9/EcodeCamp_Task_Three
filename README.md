# EcodeCamp_Task_Three


This repository contains the Jupyter Notebook `Breast_Cancer.ipynb`, which demonstrates the use of Recursive Feature Elimination (RFE) for feature selection in a breast cancer diagnosis project. The notebook performs feature selection with Logistic Regression, Decision Tree and SVM to identify the most significant features contributing to the classification task.

## Contents

- **Breast_Cancer.ipynb**: The main notebook that performs the following tasks:
  - Load and preprocess the breast cancer dataset.
  - Apply Recursive Feature Elimination (RFE) with Logistic Regression.
  - Select the top features that contribute to accurate predictions.
  - Evaluate the model's performance using the selected features.
  
## Key Features

- **RFE**: Recursive Feature Elimination is a feature selection technique that recursively removes less important features and builds the model with the remaining ones. This process is repeated until the optimal number of features is selected.
  
- **Dataset**: The dataset used in this project contains multiple features like `radius_mean`, `texture_mean`, `perimeter_mean`, and many others related to breast cancer diagnosis.

- **Model Evaluation**: After feature selection, Logistic Regression, Decision Tree and SVM are used to predict the diagnosis and evaluate the accuracies of models.


