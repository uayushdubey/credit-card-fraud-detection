# Credit Card Fraud Detection

## Objective
The goal is to build a machine learning model that can distinguish between fraudulent and legitimate transactions based on transaction data (amount, merchant info, timestamps, etc.).

The expected outcome is a fraud detection system that:
- Minimizes false positives while maximizing fraud detection accuracy.
- Provides analysis and explanation for misclassifications.

## How to Run

1. Clone this repository:

    ```bash
    git clone https://github.com/uayushdubey/credit-card-fraud-detection.git
    cd credit-card-fraud-detection
    ```

2. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

3. Place the dataset `fraudTest.csv` inside the `data/` folder. Given the Kagal URL download it from there.

4. Open and run the notebook:

    ```bash
    jupyter notebook growth_linkassign.ipynb
    ```

## Features

- Data preprocessing and feature encoding
- Random Forest classification model
- Confusion matrix, ROC curve, and feature importance plots
- Misclassification analysis and interpretation
- Well-structured, clean, and fully commented code

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
