# PCA and Logistic Regression on Cancer Dataset
## Overview
This project addresses the growing number of referrals at the Anderson Cancer Center by identifying essential variables for securing donor funding. Principal Component Analysis (PCA) is used to reduce the dimensionality of the cancer dataset and identify influential variables. Logistic regression is then applied to predict cancer diagnoses based on the reduced dataset.

## Steps
## PCA Implementation:
- PCA was applied to the breast cancer dataset from sklearn.datasets.
- After standardizing the dataset to ensure equal feature contribution, PCA reduced the dataset to two principal components.
- The first component explained 44.27% of the variance, while the second component explained 18.97%, capturing a total of 63.2% of the variance.

## Dimensionality Reduction and Visualization
- The dataset was reduced to two components.
- A scatter plot visualized the relationship between these two components, color-coding data points by cancer diagnosis (benign or malignant).
- The separation of the two classes in the plot demonstrated PCA’s ability to retain meaningful information.

## Logistic Regression
- Logistic regression was used to predict cancer diagnoses based on the two PCA components.
- The dataset was split into a training set (70%) and a test set (30%).
- The model achieved a test accuracy of 97.08%, indicating effective classification based on the reduced data.

## Interpretation of Results
## Explained Variance Ratio
- The first two PCA components explain 63.2% of the total variance, meaning that a substantial portion of the original data is captured in these two components.

## PCA Scatter Plot
- The scatter plot shows a clear separation between benign and malignant cases, suggesting that the two components retain enough information to distinguish between these classes.

## Logistic Regression Accuracy
- The logistic regression model achieved an accuracy of 97.08%, demonstrating that the two PCA components retain sufficient information for accurate classification of cancer diagnoses.

## Files
- `pca_logistic_regression.py` : Contains the code for PCA implementation and logistic regression on the cancer dataset.
- `README.md` : Provides an overview and explanation of the project.

## How to Run
- Upload the `pca_logistic_regression.py` to google coloab, select a python runtime and run it
