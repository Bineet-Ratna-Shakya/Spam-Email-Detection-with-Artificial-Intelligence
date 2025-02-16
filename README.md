# Spam Email Detection

## Overview
This project uses Machine Learning for spam email detection. Various algorithms like Naïve Bayes, Logistic Regression, Decision Tree, SVM, and Random Forest are compared to classify emails as spam or not.

## Dataset
- **Source**: Publicly available spam dataset.
- **Features**: Email text.
- **Labels**: Spam or Not Spam.

## Methodology
1. **Data Preprocessing**
   - Text cleaning, tokenization, and vectorization.
   - Feature extraction using TF-IDF.

2. **Model Training & Evaluation**
   - Algorithms: Naïve Bayes, SVM, Logistic Regression, Decision Tree, Random Forest.
   - Metrics: Accuracy, Precision, Recall, F1-score.
   - Cross-validation to ensure robustness.

3. **Results**
   - Best model: XG Boost
   - Highest accuracy: Naive Bayes

## Conclusion
Machine Learning effectively classifies spam emails. Future improvements may involve deep learning models like Bi-LSTM.

## Dependencies
- Python, Scikit-Learn, Pandas, Numpy
- Jupyter Notebook / Google Colab for experimentation
