#  Assignment 06 — Logistic Regression with Train/Test Split Analysis

##  Overview
This assignment focuses on implementing **Logistic Regression** using a predefined machine learning library and analyzing the effect of different **training–testing split ratios** on model performance.

The goal is to understand how data partitioning impacts:
- Model accuracy
- Precision, recall, and F1-score
- Generalization ability

---

##  What I Learned
- Difference between Linear and Logistic Regression  
- Binary classification using Logistic Regression  
- Importance of train/test split ratios  
- Evaluating models using classification metrics  
- Overfitting and underfitting based on split size  

---

##  Technologies Used
- Python 3.x  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  

---

##  Folder Structure
Assignment-06-Logistic-Regression-Train-Test-Analysis/
│── lab6.ipynb
│── dataset.csv (optional)
│── README.md
│── requirements.txt

yaml
Copy code

---

##  How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
```
2. Open the notebook
bash
Copy code
jupyter notebook lab6.ipynb
 Key Tasks Performed
Dataset loading and preprocessing

Feature–target separation

## Logistic Regression model training

## Experimenting with multiple train/test splits

60–40

70–30

80–20

## Performance comparison using:

Accuracy

Confusion Matrix

Precision, Recall, F1-score

## Observations
Smaller training sets may underfit

Larger training sets improve generalization

Optimal split balances bias and variance
