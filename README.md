# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. Since fraudulent transactions represent only a tiny fraction of all transactions, the dataset is highly imbalanced. The project demonstrates how to preprocess such data, train a machine learning model, and evaluate its performance using appropriate classification metrics.

A **Random Forest Classifier** was used to classify transactions as either **Legitimate** or **Fraudulent**, achieving excellent performance while maintaining high precision and recall for the minority class.

---

## 📂 Dataset

This project uses the **Credit Card Fraud Detection** dataset downloaded from **Kaggle**.

- **Total Transactions:** 284,807
- **Fraudulent Transactions:** 492
- **Legitimate Transactions:** 284,315

The dataset contains anonymized numerical features (`V1`–`V28`), along with **Time**, **Amount**, and the target variable **Class**.

- **Class = 0** → Legitimate Transaction
- **Class = 1** → Fraudulent Transaction

> **Note:** The dataset is not included in this repository due to licensing and size considerations. You can download it from Kaggle and place it in the project directory before running the notebook.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Project Workflow

- Data Loading
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Train-Test Split
- Random Forest Model Training
- Model Evaluation
- Performance Analysis

---

## 🤖 Machine Learning Model

- Random Forest Classifier

---

## 📊 Model Performance

| Metric | Score |
|---------|--------|
| Accuracy | **99.96%** |
| Precision | **95%** |
| Recall | **78%** |
| F1-Score | **85%** |
| ROC-AUC | **0.97** |

> Results may vary slightly depending on random initialization and train-test split.

---

## 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 📁 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── credit_card_fraud_detection.ipynb
├── README.md
├── requirements.txt
└── analysis
```

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/sankalpvaish43/Credit-Card-Fraud-Detection.git
```

Navigate to the project directory:

```bash
cd Credit-Card-Fraud-Detection
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

## 🙏 Acknowledgements

This project uses the **Credit Card Fraud Detection** dataset downloaded from **Kaggle**. Thanks to the dataset contributors for making it publicly available for research and educational purposes.

---

## 👨‍💻 Author

**Sankalp Vaish**

B.Tech CSE (Artificial Intelligence)

GitHub: https://github.com/sankalpvaish43
