# Predicting Credit Card Defaulters using Random Forest and XGBoost Classifiers

This repository contains a machine learning project to predict credit card default behavior based on financial and demographic data. The project compares the performance of Random Forest and XGBoost classifiers using key evaluation metrics.

## Dataset

The dataset used in this project is `Random-Forest-and-XG-Boost-Classifier-Model_dataset.xlsx`, which includes the following fields:

- `default`: Target variable indicating if the user defaulted (1) or not (0).
- `student`: Indicates whether the user is a student (Yes/No).
- `balance`: Outstanding balance on the credit card.
- `income`: User's annual income.

Key libraries include:

- `numpy`
- `pandas`
- `scikit-learn`
- `xgboost`
- `matplotlib`
- `seaborn`

## Model Training

The project implements and compares the following classifiers:

- **Random Forest Classifier:** An ensemble learning method based on decision trees.
- **XGBoost Classifier:** An advanced gradient boosting algorithm that offers high performance.

## Evaluation

The models were evaluated using the following metrics:

- **Accuracy:** Measures the percentage of correctly classified instances.
- **Confusion Matrix:** Provides a detailed breakdown of true positive, true negative, false positive, and false negative predictions.
- **F1 Score:** Offers a harmonic mean of precision and recall.
- **AUC-ROC:** Evaluates the classifier's ability to distinguish between classes. The ROC curve was plotted for visualization.
