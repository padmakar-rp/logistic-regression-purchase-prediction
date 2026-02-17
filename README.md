# logistic-regression-purchase-prediction
A simple machine learning project that predicts whether a customer will purchase a product based on their age and salary using Logistic Regression. Includes data preprocessing, model training, evaluation, and visualization of the decision boundary.

[ created using google colob ]

# Logistic Regression Purchase Prediction

This project demonstrates how to use **Logistic Regression** to predict customer purchase behavior based on their **Age** and **Salary**. The project includes data preprocessing, model training, evaluation, and visualization of the decision boundary.

## Dataset
The dataset consists of the following columns:

- `Age`: Age of the customer
- `Salary`: Annual salary of the customer
- `Purchased`: Whether the customer purchased the product (0 = No, 1 = Yes)

```python
data = {
    "Age": [22, 25, 47, 52, 46, 56, 48, 55, 23, 26, 30, 60],
    "Salary": [20000, 30000, 80000, 90000, 70000, 100000, 85000, 95000, 25000, 28000, 40000, 120000],
    "Purchased": [0, 0, 1, 1, 1, 1, 1, 1, 0, 0, 0, 1]
}
```

## Features
- Age
- Salary

## Target
- Purchased (0 = No, 1 = Yes)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/your-username/logistic-regression-purchase-prediction.git
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Run the script:
```bash
python logistic_regression_purchase.py
```
2. The script will:
   - Scale the features
   - Split data into training and testing sets
   - Train a Logistic Regression model
   - Evaluate the model
   - Plot the decision boundary

## Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report

## Visualization
The decision boundary of the Logistic Regression model is plotted, showing the separation between customers who purchased and those who did not.

## Dependencies
- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn

