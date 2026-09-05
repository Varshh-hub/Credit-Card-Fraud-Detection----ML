# Credit Card Fraud Detection using Machine Learning

## Overview

Credit card fraud is a major financial security problem where unauthorized transactions can cause significant losses. This project uses **Machine Learning** to automatically classify credit card transactions as either **Normal** or **Fraudulent**.

The project uses **Logistic Regression** to identify patterns in transaction data and predict whether a transaction is fraudulent.

---

## Problem Statement

The goal of this project is to develop a Machine Learning classification model that can:

* Detect fraudulent credit card transactions
* Classify transactions as **Normal** or **Fraud**
* Handle highly imbalanced transaction data
* Evaluate the performance of the trained model
* Perform manual testing using transaction values

---

## Machine Learning Model

The project uses:

* **Logistic Regression**

Logistic Regression is used as the classification algorithm to predict whether a credit card transaction belongs to the **Normal** or **Fraud** class.

## Data Preprocessing

The following preprocessing steps are performed:

1. Load the dataset
2. Check for missing values
3. Remove duplicate records
4. Separate features and target
5. Split the data into training and testing sets
6. Scale the numerical features using `StandardScaler`
7. Train the Logistic Regression model

---

## Manual Testing

The project includes manual testing using individual transaction values.

Example outputs:

```text
Prediction: NORMAL
```

or

```text
Prediction: FRAUD
```

This allows the trained Logistic Regression model to be tested with individual transaction values.

---

## Results

The Logistic Regression model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

For fraud detection, **Precision and Recall** are particularly important because the dataset is highly imbalanced.

---

## Conclusion

This project demonstrates how **Logistic Regression** can be applied to credit card transaction data to detect potentially fraudulent transactions. The trained model classifies transactions as **Normal** or **Fraudulent** and provides a foundation for an automated credit card fraud detection system.

---

## Author

**Varsha**

AI & ML Graduate | Junior Data Scientist & Machine Learning Engineer | Python | SQL | Excel | Power BI | Prompt Engineer | Front-End Developer
