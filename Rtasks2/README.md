# 🛒 Online Shoppers Purchase Intention Prediction

## 📌 Project Overview
This project predicts whether an online shopper will generate revenue (make a purchase) based on their browsing behavior using Machine Learning. The goal is to classify customer sessions into **Revenue = True** or **Revenue = False**.

---

## 🎯 Objective
- Predict customer purchase intention.
- Analyze browsing behavior affecting online purchases.
- Build a classification model with good prediction accuracy.

---

## 📂 Dataset
**Dataset Name:** Online Shoppers Intention Dataset

### Features
- Administrative
- Administrative_Duration
- Informational
- Informational_Duration
- ProductRelated
- ProductRelated_Duration
- BounceRates
- ExitRates
- PageValues
- SpecialDay
- Month
- OperatingSystems
- Browser
- Region
- TrafficType
- VisitorType
- Weekend

### Target Variable
- **Revenue**
  - True → Customer purchased.
  - False → Customer did not purchase.

---

## 🛠 Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🤖 Machine Learning Model
**Algorithm Used:**
- Logistic Regression

---

## 📊 Data Preprocessing
- Loaded dataset
- Encoded categorical variables using LabelEncoder
- Split dataset into training and testing sets
- Applied StandardScaler for feature scaling

---

## 📈 Model Evaluation
The model was evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix

**Expected Accuracy:** 85%–90%

---

## 📉 Visualizations
Two visualizations were generated:

### 1. Confusion Matrix
Displays the number of correct and incorrect predictions.

### 2. Feature Importance
Shows which features contribute most to predicting customer purchases.

---

## 📦 Libraries Used

```python
pandas
numpy
matplotlib
scikit-learn
```

---

## ▶️ Steps to Run

1. Upload the dataset.
2. Install required libraries.
3. Run the preprocessing code.
4. Train the Logistic Regression model.
5. Evaluate the model.
6. View the graphs and accuracy.

---

## 📌 Output
- Purchase Prediction (Revenue)
- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance Graph

---

## 🚀 Future Enhancements
- Compare Logistic Regression with Random Forest and XGBoost.
- Perform Hyperparameter Tuning.
- Build a web application using Flask or Streamlit.
- Deploy the model for real-time predictions.

---

## 👩‍💻 Author

**Mathan R**

Bachelor of Computer Applications (BCA)

Kamaraj College
