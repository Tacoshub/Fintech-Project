# Financial Market Analysis with Lasso Regression, Kalman Filters, and Neural Networks

This repository contains the implementation of our project focused on financial market analysis using a combination of Lasso Regression, Kalman Filters, and Neural Networks. The code is written in Python and organized using Jupyter Notebooks, enabling detailed comments and explanations.

---

## Recommended Order to Open the Notebooks

To understand the workflow and methodology, we recommend opening the notebooks in the following order:

1. **`Lasso Regression Validation`**:  
   This notebook trains a linear regression model with Lasso penalty for both weekly and monthly rebalancing cases.

2. **`Lasso Regression Test`**:  
   This notebook evaluates the performance of the Lasso Regression model on the test dataset.

3. **`Feature Selection`**:  
   This notebook explains the rationale behind selecting features for the Kalman Filter.

4. **`Kalman Filter`**:  
   This notebook implements the Kalman Filter and evaluates its base performance on the validation set without parameter optimization. The goal is to compare its behavior with the Lasso Regression model.

5. **`Neural Network Anomaly Detection`**:  
   This notebook implements and optimizes a neural network for predicting future market anomalies. At the end of the code, an Excel file named `VALORI_PREDETTI` is created. For convenience, this file is already included in the repository to avoid file creation issues during execution.

6. **`Kalman Filter Validation`**:  
   This notebook identifies the optimal hyperparameter for the classifier threshold to refine the Kalman Filter model.

7. **`Kalman Filter Test`**:  
   This notebook tests the new Kalman Filter model's performance under varying values of the alpha exposure parameter.

---

## Project Presentation

- A PDF presentation summarizing the project is available in the repository for reference.  

---

## Outputs

- The project outputs include:
  - A trained Lasso Regression model.
  - A Kalman Filter implementation with validated and tested performance.
  - Anomaly detection results saved in the `VALORI_PREDETTI` Excel file.
  - Performance comparisons and insights for various financial modeling approaches.

---
