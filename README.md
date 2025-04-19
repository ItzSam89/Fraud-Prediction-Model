# Fraud Prediction Model Using Random Forest Classifier

This project aims to predict fraudulent transactions using a machine learning model based on the **Random Forest Classifier**. The model uses historical transaction data to classify transactions as either **fraudulent** or **non-fraudulent**.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [License](#license)

## Project Overview
Fraudulent transactions are a significant issue in the financial sector, and detecting such fraudulent activities is crucial for ensuring the integrity of online payment systems. This project uses machine learning techniques to detect fraud based on historical transaction data. The **Random Forest Classifier** is used to build a robust model that can identify patterns in transaction data to predict fraud.

## Dataset
The dataset used in this project is a collection of transaction records, with features such as:
- Step
- Type
- amount
- nameOrig
- oldbalanceOrg
- newbalanceOrig
- nameDest
- oldbalanceDest
- newbalanceDest
- isFraud
- isFlaggedFraud
You can find all of these and their descriptions in the data dictionary
> Note: The dataset can be found on this drive link ##https://drive.google.com/file/d/1N7xD97XXxkORcxFbDZcUQq--TKd1CpxN/view?usp=sharing
## Installation
Please make sure you have Jupyter notebook (or any other environment to open ipynb file) installed.
### Prerequisites
Ensure you have the following Python libraries installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install them using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
