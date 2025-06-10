# Income Classification using Machine Learning

This project is part of my journey to **learn and practice Machine Learning**, specifically focusing on **Classification** techniques.

It applies data preprocessing, feature scaling, and machine learning models to classify whether an individual's income exceeds $50K/yr based on census data.

## 📘 Project Overview

The dataset used is the [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult), which includes demographic and employment-related information such as age, education, occupation, and hours worked per week.

The notebook demonstrates:
- Data cleaning and preprocessing
- Feature encoding
- Train/validation/test split
- Feature scaling using `StandardScaler`
- Class imbalance handling using `RandomOverSampler`
- Evaluation of model performance

## 📁 Dataset

You can download the original dataset from the UCI Machine Learning Repository:

🔗 **[Adult Income Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/adult/)**

The dataset consists of:
- `adult.data`: Training data
- `adult.test`: Test data
- `adult.names`: Attribute information

## 🧰 Technologies Used

- Python
- pandas
- numpy
- scikit-learn
- imbalanced-learn (`RandomOverSampler`)
- matplotlib / seaborn (optional for visualization)

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/income-classification.git
   cd income-classification
