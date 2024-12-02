# Neural-Network-Cardiopathy-Classification

### Purpose and Scope:
The goal of this project is to develop a high-performance neural network to classify individuals based on their risk of cardiopathy (high risk: 1 or low risk: 0). The project includes exploratory data analysis, handling categorical data, implementing and tuning a neural network, and evaluating its performance using several metrics. Additionally, the performance of the neural network is compared with a classical logistic regression model to assess its effectiveness.

### Key Concepts Covered:
Exploratory Data Analysis:
Typology of variables
Handling missing values
Distribution analysis of observations (e.g., boxplots)
Data Preprocessing:
Resolution of categorical data issues
Data splitting (80% training, 20% testing) with class proportion preserved
Neural Network Implementation:
Hyperparameter tuning for performance optimization
Overfitting reduction techniques
Model Evaluation:
Classification errors
Detailed confusion matrix
ROC curve and AUC evaluation
Model Comparison:
Neural network vs. classical logistic regression

### Repository Structure:
Script.ipynb: The Python notebook containing the complete implementation of the cardiopathy classification task, including data preprocessing, model development, and evaluation.
requirements.txt: A file listing all the dependencies (packages and versions) required to run the project.
Assignment.pdf: The challenge assignment document detailing the task requirements and dataset information.
data.txt: The full dataset (HD_Complete_Data) provided for model development, containing both predictors and the corresponding target values.
Xtest.txt: The test dataset containing only predictors, used for generating final predictions.
my_predictions.txt: The final predictions made on Xtest.txt for evaluation in the challenge.
