# NLP Project: Language Modeling and Classification

## Overview
This LAB involves language modeling and classification tasks using various machine learning algorithms and NLP techniques. The datasets used are:
- [Short Answer Grading Dataset](https://github.com/dbbrandt/short_answer_granding_capstone_project/blob/master/data/sag/answers.csv) for regression tasks.
- [Twitter Entity Sentiment Analysis Dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis) for classification tasks.

## Table of Contents
1. [Preprocessing](#preprocessing)
2. [Data Vectorization](#data-vectorization)
3. [Model Training](#model-training)
4. [Model Evaluation](#model-evaluation)
5. [Results](#results)
6. [Conclusion](#conclusion)

## Preprocessing
The preprocessing pipeline includes:
- Tokenization
- Stemming
- Lemmatization
- Stop words removal
- Text discretization

## Data Vectorization
I used the following techniques for vectorization:
- Word2Vec (CBOW and Skip Gram)
- Bag of Words
- TF-IDF

## Model Training
For regression tasks, I trained:
- Support Vector Regression (SVR)
- Naive Bayes
- Linear Regression
- Decision Tree

For classification tasks, I trained:
- Support Vector Machine (SVM)
- Naive Bayes
- Logistic Regression
- Ada Boosting

## Model Evaluation
The models were evaluated using:
- Regression: Mean Squared Error (MSE), Root Mean Squared Error (RMSE)
- Classification: Accuracy, Loss, F1 Score, BLEU score

## Results
The best performing models were:
- Regression: [SVR] WITH LOWEST MSE AND RMSE
- Classification: [SVM] with Accuracy of [0.537] :Interpretation of Results

    Logistic Regression and SVM showed higher accuracy and classification metrics compared to Naive Bayes and AdaBoost.
    AdaBoost and Naive Bayes provided valuable insights, particularly in classifying majority classes.
    Consider task-specific requirements and the balance between precision, recall, and accuracy when selecting the best model for deployment.

## Conclusion
This project provided insights into the effectiveness of various NLP preprocessing techniques and vectorization methods. The use of Word2Vec embeddings improved model performance significantly. 

## Acknowledgements
Special thanks to Pr. Elaachak Lotfi for his guidance and support throughout this project.
