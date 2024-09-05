PCA and Logistic Regression on Cancer Dataset
Overview
This project addresses the growing number of referrals at the Anderson Cancer Center by identifying essential variables for securing donor funding. Principal Component Analysis (PCA) is used to reduce the dimensionality of the cancer dataset and identify influential variables. Logistic regression is then applied to predict cancer diagnoses based on the reduced dataset.

Steps
PCA Implementation:
PCA was applied to the breast cancer dataset from sklearn.datasets. After standardizing the dataset to ensure equal feature contribution, PCA reduced the dataset to two principal components. The first component explained 44.27% of the variance, while the second component explained 18.97%, capturing a total of 63.2% of the variance.
