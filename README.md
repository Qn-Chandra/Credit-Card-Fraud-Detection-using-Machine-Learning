# 💳 Credit Card Fraud Detection System

### This project focuses on building a Machine Learning based Credit Card Fraud Detection System that can identify potentially fraudulent transactions from legitimate ones.
### Credit card fraud is one of the most significant financial threats in digital transactions. Detecting fraudulent transactions is challenging because fraud cases are extremely rare compared to normal transactions, which results in a highly imbalanced dataset.
### The objective of this project is to build a reliable classification model that can analyze transaction patterns and predict whether a transaction is fraudulent or legitimate, helping financial institutions reduce losses and improve security.

# Problem Statement

### In real-world financial datasets, fraudulent transactions make up only a very small portion of the total data. This creates a class imbalance problem, where machine learning models may become biased toward the majority class (legitimate transactions).

# Challenge

### The original dataset was highly imbalanced, with fraudulent transactions representing only a very small fraction of the data.

### To address this challenge:

### 1) The dataset was balanced before training the model.

### 2) Techniques such as resampling / equal class sampling were used to ensure that the model learns patterns from both fraud and non-fraud transactions effectively.

### 3) This step significantly improved the model’s ability to detect fraudulent cases.

# Technologies Used
### Python
### NumPy
### Pandas
### Scikit-learn
### Jupyter Notebook

# Approach & Methodology
### 1️⃣ Data Preprocessing

### Cleaned and prepared the dataset for machine learning.
### Checked for missing values and ensured data consistency.
### Performed feature separation between input variables and target variable.

### 2️⃣ Handling Imbalanced Dataset

### The original dataset was highly imbalanced, with fraudulent transactions representing only a very small fraction of the data.
### To address this challenge:
### The dataset was balanced before training the model.
### Techniques such as resampling / equal class sampling were used to ensure that the model learns patterns from both fraud and non-fraud transactions effectively.
### This step significantly improved the model’s ability to detect fraudulent cases.

### 3️⃣ Train-Test Split

### The dataset was divided into two parts:
### Training Dataset → Used to train the model
### Testing Dataset → Used to evaluate model performance on unseen data

# Machine Learning Model

### The model used in this project is:
### Logistic Regression
### Logistic Regression is a widely used classification algorithm that predicts the probability of a transaction belonging to a specific class (Fraud or Non-Fraud). It works well for binary classification problems and provides interpretable results.

# Model Performance

### After training and evaluating the model:
### Training Accuracy: 94%
### Testing Accuracy: 91%
### The small difference between training and testing accuracy indicates that the model is generalizing well and not significantly overfitting.











