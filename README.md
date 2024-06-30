# MIIMANSA_AI

Abstract Classification into Predefined Domains

# Problem Statement
Given an abstract of a paper, the objective is to classify it into one of the seven predefined domains:

Computation and Language (CL)

Cryptography and Security (CR)

Distributed and Cluster Computing (DC)

Data Structures and Algorithms (DS)

Logic in Computer Science (LO)

Networking and Internet Architecture (NI)

Software Engineering (SE)

# Dataset

The dataset consists of abstracts of research papers and their corresponding target domains. It is divided into a training set and a test set.

# Approach
1. Text Preprocessing
Convert text to lowercase.
Remove non-alphanumeric characters.
Remove stop words.
Lemmatize the words.
2. Feature Extraction
Use TF-IDF Vectorizer to transform the text data into numerical features.
3. Handling Class Imbalance
Use SMOTE (Synthetic Minority Over-sampling Technique) to handle class imbalance.
4. Model Training and Evaluation
Train multiple models: Logistic Regression, Support Vector Machine (SVM), XGBoost, and LSTM.
Evaluate models using precision, recall, F1-score, and confusion matrices.
Perform cross-validation and plot learning curves.
