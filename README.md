# Credit Card Fraud Detection Using Machine Learning

## Overview

This project is a Machine Learning-based Credit Card Fraud Detection system developed using Python and Scikit-learn. The model analyzes transaction data and predicts whether a transaction is fraudulent or legitimate.

The project demonstrates:

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature scaling
* Machine Learning model training
* Fraud prediction using Random Forest Classifier
* Model evaluation using accuracy score, confusion matrix, and classification report

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# Project Structure

```text
credit-card-fraud-detection/
│
├── assets/
│   ├── dataset-preview.png
│   ├── heatmap.png
│   ├── confusion-matrix.png
│   └── results.png
│
├── Task 5 Codsoft.ipynb
├── creditcard.csv
├── README.md
```

---

# Dataset

The dataset contains credit card transaction records with features used to identify fraudulent activities.

Dataset includes:

* Transaction details
* Scaled numerical features
* Target variable (`Class`)

  * `0` = Legitimate Transaction
  * `1` = Fraudulent Transaction

---

# Machine Learning Workflow

## 1. Data Loading

The dataset is loaded using Pandas.

## 2. Data Cleaning

* Checked missing values
* Verified dataset structure
* Performed statistical analysis

## 3. Exploratory Data Analysis

* Correlation heatmap
* Fraud vs Non-Fraud distribution
* Feature relationship analysis

## 4. Feature Scaling

Used `StandardScaler` for normalization.

## 5. Model Training

Implemented:

* Random Forest Classifier

## 6. Model Evaluation

Evaluated performance using:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

# Screenshots

## Dataset Preview

<img width="1341" height="532" alt="credit card fraud detection dataset preview" src="https://github.com/user-attachments/assets/99ad9b71-4b94-458f-8e2a-380ad94a68c0" />


---

## Correlation Heatmap

<img width="809" height="568" alt="credit card fraud detection correlation heatmap" src="https://github.com/user-attachments/assets/8b931c79-d939-4cae-9520-c49ec8dd1f8f" />


---

## Confusion Matrix

<img width="640" height="547" alt="credit card fraud detection confusion matrix" src="https://github.com/user-attachments/assets/f845eb8a-c544-47a6-9b34-9f0b42b7e561" />


---

## Fraud Detection Results

<img width="531" height="250" alt="credit card fraud detection result" src="https://github.com/user-attachments/assets/33eb088a-b758-4bd2-a522-625c9e076e09" />


---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
```

Move into the project folder:

```bash
cd credit-card-fraud-detection
```

Create virtual environment:

```bash
py -3.10 -m venv mlenv
```

Activate environment:

```bash
.\mlenv\Scripts\Activate.ps1
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

# Results

The model successfully detects fraudulent transactions using machine learning techniques and demonstrates effective classification performance.

---

# Future Improvements

* Implement Deep Learning models
* Improve class imbalance handling
* Deploy using Streamlit or Flask
* Add real-time fraud detection

---

# Author

**Kiran**

---

# GitHub Repository Description

Machine Learning project for detecting fraudulent credit card transactions using Python, Pandas, Seaborn, and Scikit-learn.
