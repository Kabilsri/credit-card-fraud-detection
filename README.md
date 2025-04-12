# 💳 Credit Card Fraud Detection

This project uses machine learning to detect fraudulent credit card transactions based on real-world anonymized data. Fraud detection is a critical application of data science that helps protect financial institutions and customers from financial loss.

---

## 📁 Project Structure


---

## 🧾 Dataset Overview

- The dataset contains transactions made by European cardholders in September 2013.
- It presents transactions that occurred in two days, with **284,807 transactions**, where **492 are frauds**.
- Features are numerical values resulting from a PCA transformation to protect confidentiality (V1 to V28), along with:
  - `Time`: Seconds elapsed between the first and current transaction
  - `Amount`: Transaction amount
  - `Class`: Target variable (`0` for valid, `1` for fraud)

> 📌 Note: The dataset is **highly imbalanced**.

---

## 🎯 Objective

To build a classification model that:
- Accurately detects fraudulent transactions
- Handles imbalanced data effectively
- Minimizes false negatives (undetected fraud)

---

## 🔍 Project Workflow

1. **Data Preprocessing**
   - Handling imbalance using undersampling/oversampling
   - Feature scaling

2. **Exploratory Data Analysis**
   - Visualizations of fraud vs. non-fraud distributions
   - Correlation heatmaps

3. **Model Building**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost (optional)

4. **Evaluation Metrics**
   - Accuracy, Precision, Recall
   - F1 Score
   - ROC-AUC Curve
   - Confusion Matrix

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
