# Topsis-On-Pretrained-Model
# Text Conversational Analysis with ML Models and TOPSIS

## Overview

This project explores the application of machine learning models to analyze text conversations, aiming to predict outcomes based on input text. It evaluates and compares the performance of Naive Bayes, SVM, Random Forest, Gradient Boosting, and Neural Network models. Additionally, the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) is implemented for model ranking.

## Dataset

The dataset comprises text conversations, with each conversation associated with a specific output. The objective is to employ machine learning techniques to predict the output based on the input text.

## Machine Learning Models

1. **Naive Bayes:**
   - A probabilistic model leveraging Bayes' theorem, suitable for text classification.

2. **Support Vector Machine (SVM):**
   - A powerful classification algorithm aiming to find a hyperplane that best separates different classes in the feature space.

3. **Random Forest:**
   - An ensemble learning method that builds multiple decision trees, enhancing accuracy and robustness.

4. **Gradient Boosting:**
   - A boosting algorithm constructing sequential weak learners, each correcting errors of the previous one.

5. **Neural Network:**
   - A deep learning model with interconnected nodes capable of learning intricate patterns in data.

## TOPSIS

In addition to machine learning models, the project implements TOPSIS for decision-making and model ranking. TOPSIS is a multi-criteria decision analysis method that aids in selecting the best alternative based on their proximity to the ideal solution.

## Workflow

1. **Data Preprocessing:**
   - Text data undergoes preprocessing, including tokenization, vectorization, and encoding of the target variable.

2. **Model Training:**
   - ML models are trained on the dataset to learn patterns and relationships between input text and output.

3. **Evaluation:**
   - Model performance is assessed using metrics like accuracy, precision, and recall on the test set.

4. **TOPSIS Implementation:**
   - TOPSIS is applied to rank models based on performance metrics. The proximity of each model to ideal and negative-ideal solutions determines their rankings.

5. **Results and Visualization:**
   - Results are saved in a CSV file for analysis. Visualizations, including bar charts, offer a clear comparison of models based on accuracy, precision, and recall.
   - 
