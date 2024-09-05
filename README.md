# PCA and Logistic Regression on Cancer Dataset
## Overview
This project aims at catering for the increasing number of referrals in the Anderson Cancer Center by establishing relevant variables that would be useful in the search for donor funding. The basic procedure of Principal Component Analysis (PCA) is applied to reduce the dimensions of cancer dataset and to assess the significance of variables. The resulting variables are then fed to logistic regression, through which cancer diagnosis is predicted from the newly formed reduced dataset.

## Steps
## PCA Implementation:
- PCA was applied to the breast cancer dataset from sklearn.datasets.
- Which I then standardized for equal contribution to the features and consequently transforming the data to two principal components using PCA.
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
