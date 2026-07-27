# Credit Card Fraud Detection using Machine Learning

## Project Overview

This project focuses on finding credit card transactions using Machine Learning. Because fraudulent transactions are a small part of all transactions the data set is very unbalanced. The project shows how to prepare this kind of data train a machine learning model and check how well the model works using the classification measurements.

A Random Forest Classifier was used to decide if transactions are Legitimate or Fraudulent. This model worked well and kept high precision and recall for the small group.

---

## Dataset

This project uses the Credit Card Fraud Detection data set that was taken from Kaggle.

- Total Transactions: 284,807

- Fraudulent Transactions: 492

- Legitimate Transactions: 284,315

The data set has features (V1 to V28) along with Time, Amount and the target variable Class.

- Class = 0 → Legitimate Transaction

- Class = 1 → Fraudulent Transaction

> Note: The data set is not part of this repository because of licensing and size reasons. You can get it from Kaggle. Put it in the project folder before running the notebook.

---

## Technologies Used

- Python

- Pandas

- NumPy

- Matplotlib

- Scikit-learn

- Jupyter Notebook

---

## Project Workflow

- Data Loading

- Exploratory Data Analysis (EDA)

- Data Preprocessing

- Train Test Split

- Random Forest Model Training

- Model Evaluation

- Performance Analysis

---

## Machine Learning Model

- Random Forest Classifier

---

## Model Performance

| Metric | Score |

|---------|--------|

| Accuracy | **99.96%** |

| Precision **95%** |

| Recall | **78%** |

F1-Score | **85%** |

ROC-AUC | **0.97** |

> Results might be a little different depending on how things are randomly set up and how the data is split.

---

## Evaluation Metrics

The model was checked using:

- Accuracy

- Precision

- Recall

- F1-Score

- ROC-AUC Score

- Confusion Matrix

---

## Project Structure

```

Credit-Card-Fraud-Detection/

│

├── credit_card_fraud_detection.ipynb

├── README.md

├── requirements.txt

└── analysis

```

---

## How to Run

Clone the repository:

```bash

git clone https://github.com/sankalpvaish43/Credit-Card-Fraud-Detection.git

```

Go to the project folder:

```bash

cd Credit-Card-Fraud-Detection

```

Install the needed libraries:

```bash

pip install -r requirements.txt

```

Start Jupyter Notebook:

```bash

notebook

```

## Acknowledgements

This project uses the Credit Card Fraud Detection data set that was taken from Kaggle. Thanks to the people who made the data set available, for research and learning.

---

## Author

**Sankalp Vaish**

B.Tech CSE (Artificial Intelligence)

GitHub: https://github.com/sankalpvaish43
