# 🏦 Customer Churn Prediction using Machine Learning

> A Machine Learning project to predict whether a bank customer will leave the bank (Churn) or continue using its services based on customer information.

---

## 📌 Project Overview

Customer churn prediction is an important problem in the banking industry. This project uses Machine Learning to analyze customer data and predict whether a customer is likely to leave the bank.

The model is trained using customer details such as credit score, age, balance, salary, number of products, and account activity.

---

## 🎯 Objective

- Predict customer churn using Machine Learning.
- Identify customers who are likely to leave the bank.
- Help banks improve customer retention strategies.

---

## 📂 Dataset Information

| Feature | Description |
|----------|-------------|
| customer_id | Unique customer ID |
| credit_score | Customer credit score |
| country | Customer's country |
| gender | Male / Female |
| age | Customer age |
| tenure | Years with the bank |
| balance | Account balance |
| products_number | Number of bank products |
| credit_card | Has credit card (0/1) |
| active_member | Active member (0/1) |
| estimated_salary | Estimated annual salary |
| churn | Target variable (0 = Stay, 1 = Leave) |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Machine Learning Workflow

```
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Label Encoding
   │
   ▼
Feature Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Random Forest Classifier
   │
   ▼
Prediction
   │
   ▼
Model Evaluation
```

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were created:

- 📈 Customer Churn Distribution
- 🔥 Correlation Heatmap
- 👥 Churn by Gender
- 📊 Age Distribution
- 💰 Balance Distribution
- ⭐ Feature Importance
- 📉 Confusion Matrix

---

## 📷 Project Output

### Customer Churn Distribution

![Customer Churn](images/class_distribution.png)

---

### Correlation Heatmap

![Heatmap](images/correlation_heatmap.png)

---

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

### Feature Importance

![Feature Importance](images/feature_importance.png)

---

### Age Distribution

![Age Distribution](images/age_distribution.png)

---

### Balance Distribution

![Balance Distribution](images/balance_distribution.png)

---

### Churn by Gender

![Gender Churn](images/gender_churn.png)

---

## 📈 Model Performance

| Metric | Value |
|---------|--------|
| Algorithm | Random Forest Classifier |
| Problem Type | Binary Classification |
| Accuracy | **86%** (Approx.) |

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Churn_Modelling.csv
├── Customer_Churn_Prediction.ipynb
├── README.md
│
├── images/
│   ├── class_distribution.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   ├── age_distribution.png
│   ├── balance_distribution.png
│   └── gender_churn.png
│
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the notebook

```bash
jupyter notebook
```

Open

```
Customer_Churn_Prediction.ipynb
```

Run all cells.

---

## 📌 Future Enhancements

- Hyperparameter Tuning
- XGBoost Classifier
- LightGBM
- Streamlit Deployment
- Flask Web Application

---

## 👩‍💻 Author

**Mathan R**

**Bachelor of Computer Applications (BCA)**

**Kamaraj College**

**Year of Passing:** 2027

---

## ⭐ Support

If you found this project useful, please ⭐ the repository and share it with others.
