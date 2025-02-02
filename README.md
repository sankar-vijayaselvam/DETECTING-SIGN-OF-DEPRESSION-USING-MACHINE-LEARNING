# DETECTING-SIGN-OF-DEPRESSION-USING-MACHINE-LEARNING

# Project Description

This project applies machine learning techniques to detect depression indicators in social media posts. By leveraging advanced text processing and classification models, it aims to provide a data-driven approach to mental health analysis.

# Purpose

- The purpose of this study is to:
- Detect depression levels in social media messages.
- Utilize machine learning models for automated classification.
- Improve early intervention and support for individuals at risk.

# Key Insights

- Categorized Social Media Data: Messages are classified into three categories—Not Depressed, Somewhat Depressed, and Severely Depressed.

- Feature Extraction Techniques: TF-IDF, Count Vectorizer, and Hashing Vectorizer are used to represent text data numerically.

- Machine Learning Models: Trained and evaluated models include Logistic Regression, Random Forest, Decision Tree, Gaussian Naive Bayes, and Multinomial Naive Bayes.

- Performance Metrics: Accuracy, precision, recall, F1 score, and confusion matrix are used for model evaluation.

- Best Performing Model: The Random Forest model with Count Vectorizer achieved the highest accuracy of 92.99% on the development dataset.


# Dataset Details

- The dataset used in this study includes:

- Social Media Posts: Collected and labeled into three depression severity categories.

- Preprocessed Text Data: Cleaned and transformed messages for feature extraction.

- Training and Evaluation Splits: Ensuring effective model learning and validation.

# How to Use

- Install the necessary dependencies.
- Load the dataset and apply text pre-processing techniques.
- Extract features using TF-IDF, Count Vectorizer, or Hashing Vectorizer.
- Train and evaluate machine learning models.
- Analyze results using performance metrics.

# Prerequisites

- Python 3.x

- Scikit-learn

- Pandas & NumPy

- NLTK & SpaCy

# Future Enhancements

- Incorporation of deep learning models for improved classification.
- Expansion of the dataset for better generalization.
- Real-time monitoring and detection system integration.
