# Diabetes Prediction Model PIMA Indian Diabetes dataset

## Overview
This repository contains Python code for training and evaluating neural network models on the Pima Indians Diabetes dataset, focusing on handling class imbalance and small dataset challenges. The project implements a two-stage grid search for hyperparameter tuning, evaluates model performance using confusion matrices, classification reports, and ROC curves, and includes visualizations to assess model effectiveness.

## Features
- Dataset: Pima Indians Diabetes dataset (class-imbalanced, small sample size).
- Models: Neural networks with varying architectures (2-4 layers).
- Hyperparameter Tuning: Two-stage grid search for optimizing neuron units, learning rate, batch size, epochs, dropout, and L2 regularization.
- Evaluation: Metrics include confusion matrix, classification report, ROC AUC, with visualizations for interpretability.

Key Results:
- Best Validation Accuracy: 81.32%
- Test Accuracy: 75.82%
- ROC AUC: 0.813
- Confusion Matrix: TN=55, FP=6, FN=16, TP=14

## Future Improvements
- Apply SMOTE or weighted loss to address class imbalance.
- Increase dataset size or use data augmentation.
- Explore alternative models (e.g., ensemble methods).
- Implement k-fold cross-validation for robustness.


## License

[MIT](https://choosealicense.com/licenses/mit/)
