Heart Disease Prediction – Machine Learning and Deep Learning Models

Project Overview

This project investigates the use of machine learning and deep learning models to predict the likelihood of heart disease using the UCI Heart Disease dataset.
The work compares traditional classifiers (Decision Tree, Random Forest, Naïve Bayes) with advanced deep learning models (Artificial Neural Network and LSTM).
The aim is to identify the most reliable model for clinical decision support.

Models Implemented

Decision Tree – Simple and interpretable baseline, but unstable on small data.

Random Forest – Stronger ensemble method, reduced variance, more balanced.

Naïve Bayes – Probabilistic benchmark; very high precision but low recall.

Artificial Neural Network (Multilayer Perceptron) – Balanced accuracy, recall, and precision.

LSTM – Advanced deep learning model; strong recall and F1 but computationally expensive.

Key Results

Decision Tree: Accuracy = 80%, Recall = 71%. Misses too many disease cases.

Random Forest: Accuracy = 83%, Recall = 75%. More reliable than Decision Tree.

Naïve Bayes: Accuracy = 87%, Precision = 100%, Recall = 71%. Unsafe due to missed cases.

ANN (MLP): Accuracy = 90%, Recall = 82%, ROC-AUC = 0.96. Most balanced and reliable.

LSTM: Accuracy = 92%, Recall = 82%, F1 = 0.90. Strongest overall but heavier to train.

Final Conclusion

The Artificial Neural Network (ANN) was chosen as the best-performing model due to its balance between accuracy, recall, and clinical reliability.
The LSTM performed slightly better in some metrics but was considered too complex for the dataset.
Random Forest was identified as the strongest traditional machine learning method.

Future Work

Extend evaluation to larger, external datasets to test generalization.

Apply SHAP or LIME for better interpretability, especially for ANN.

Explore cost-sensitive training methods to reduce false negatives.


Team Members

Member 1 – Preprocessing, Decision Tree, Random Forest

Member 2 – Naïve Bayes, ANN, LSTM, Model Comparison