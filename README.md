# Credit Card Fraud Detection

A Machine Learning project that detects fraudulent credit card transactions using data preprocessing, exploratory data analysis (EDA), imbalance handling techniques, and classification algorithms. The goal is to improve transaction security by accurately identifying fraudulent activities while minimizing false positives.

---

## Project Overview

Credit card fraud is a significant challenge in the financial industry due to the highly imbalanced nature of transaction data. This project applies machine learning techniques to identify fraudulent transactions and evaluate model performance using industry-standard metrics.

The project includes:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Handling Imbalanced Data using SMOTE
- Machine Learning Model Training
- Model Evaluation and Comparison
- Data Visualization and Insights

---

## Features

- Detects fraudulent credit card transactions.
- Handles highly imbalanced datasets using SMOTE (Synthetic Minority Oversampling Technique).
- Performs comprehensive Exploratory Data Analysis (EDA).
- Trains and evaluates machine learning models.
- Provides detailed performance metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC Score
- Includes visualizations such as:
  - Transaction Distribution
  - Correlation Heatmaps
  - Confusion Matrices
  - ROC Curves

---

## Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

### Tools
- Jupyter Notebook
- Git
- GitHub

---

## Dataset

The dataset used in this project is the Credit Card Fraud Detection dataset from Kaggle.

### Dataset Information

- Total Transactions: 284,807
- Fraudulent Transactions: 492
- Fraud Rate: 0.17%
- Features: 30 anonymized features including:
  - Time
  - Amount
  - Principal Components (V1–V28)
  - Class (Target Variable)

### Class Labels

- 0 → Legitimate Transaction
- 1 → Fraudulent Transaction

> Note: The dataset is highly imbalanced, making fraud detection a challenging machine learning problem.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/Harshiithaj28/Credit_card_Fraud_Detection.git
cd Credit_card_Fraud_Detection
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter
```

---

## Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
ccfd.ipynb
```

Run all cells sequentially to:

1. Load the dataset
2. Perform data preprocessing
3. Conduct exploratory data analysis
4. Handle class imbalance using SMOTE
5. Train machine learning models
6. Evaluate model performance
7. Generate visualizations and insights

---

## Model Evaluation Metrics

The project evaluates models using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

These metrics help assess the model's ability to correctly identify fraudulent transactions while minimizing false alarms.

---

## Visualizations

The notebook includes visualizations such as:

- Transaction Distribution Analysis
- Fraud vs Non-Fraud Comparison
- Correlation Heatmap
- Feature Analysis
- Confusion Matrix
- ROC Curve
  <img width="1171" height="529" alt="image" src="https://github.com/user-attachments/assets/220402f9-64e0-4777-a110-34d7760b4ec5" />
  <img width="738" height="614" alt="image" src="https://github.com/user-attachments/assets/5110b081-59e5-4289-8c3e-8fca122e9099" />
  <img width="1122" height="727" alt="image" src="https://github.com/user-attachments/assets/06b58ef3-37da-49c1-9c8b-0c0f9c26c5d4" />
  <img width="1122" height="699" alt="image" src="https://github.com/user-attachments/assets/12b0f3d0-81a7-4ae9-92d5-0cae96233a31" />
  <img width="1129" height="701" alt="image" src="https://github.com/user-attachments/assets/da6a392d-5459-4064-9ac2-524e662f1ca1" />


---

## Repository Structure

```text
Credit_card_Fraud_Detection/
│
├── ccfd.ipynb
├── README.md
└── LICENSE
```

---

## Results

The implemented machine learning models achieve high classification performance despite the extreme class imbalance present in the dataset. The use of SMOTE and feature engineering helps improve fraud detection accuracy and recall.

---

## Future Improvements

- Real-time fraud detection system
- Deep Learning models such as ANN, Autoencoders, and LSTMs
- Model deployment using Flask, FastAPI, or Streamlit
- Explainable AI (XAI) integration
- Cloud deployment for scalable predictions

---

## Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

## Author

**Harshitha J**

GitHub: https://github.com/Harshiithaj28

Computer Science Engineering Student | Machine Learning Enthusiast
