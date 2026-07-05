# NSL-KDD Intrusion Detection using Machine Learning

## Overview

This project presents a binary intrusion detection system using the NSL-KDD dataset. Several machine learning algorithms were implemented and compared to classify network traffic into two categories:

- Normal
- Attack

The project includes data preprocessing, feature engineering, model training, performance evaluation, and result visualization.

---

## Dataset

The experiments were conducted using the **NSL-KDD** dataset, an improved version of the KDD Cup 1999 dataset widely used for intrusion detection research.

Dataset files:

- KDDTrain+.txt
- KDDTest+.txt

---

## Data Preprocessing

The following preprocessing steps were applied:

- Assigned column names
- Checked missing values
- Converted attack labels into binary classes
- Instructions for categorical features
- Feature alignment between training and testing datasets
- Standardization using StandardScaler

---

## Machine Learning Models

The following classifiers were implemented:

- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Training Time

---

## Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Project Structure

```
NSL-KDD-Intrusion-Detection
│
├── NSL_KDD.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── images
```

---

## Author

**Elham Tari /// Email: tari.elham70@gmail.com**