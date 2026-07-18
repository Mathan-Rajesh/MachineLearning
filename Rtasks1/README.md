# Bank Customer Churn Prediction using Machine Learning

## 📌 Project Overview
This project predicts whether a bank customer is likely to leave the bank (churn) using Machine Learning. The model is trained on customer information such as credit score, age, balance, gender, country, and other banking details.

---

## 🎯 Objective
To build a machine learning model that accurately predicts customer churn so banks can identify customers who are at risk of leaving and improve customer retention.

---

## 📂 Dataset
**Dataset:** Bank Customer Churn Prediction

### Features
- Customer ID
- Credit Score
- Country
- Gender
- Age
- Tenure
- Balance
- Products Number
- Credit Card Status
- Active Member
- Estimated Salary

### Target Variable
- **Churn**
  - 0 → Customer Stays
  - 1 → Customer Leaves

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📚 Machine Learning Workflow

1. Import required libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Handle categorical variables using Label Encoding
5. Remove unnecessary columns
6. Split data into training and testing sets
7. Scale features using StandardScaler
8. Train the Random Forest Classifier
9. Predict customer churn
10. Evaluate model performance

---

## 🤖 Machine Learning Model

**Algorithm Used**
- Random Forest Classifier

---

## 📊 Data Visualization

The project includes:

- Customer Churn Distribution
- Correlation Heatmap

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📁 Project Structure

```
Bank-Customer-Churn-Prediction/
│
├── Bank Customer Churn Prediction.csv
├── churn_prediction.ipynb
├── class_distribution.png
├── correlation_heatmap.png
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Bank-Customer-Churn-Prediction.git
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## 📌 Future Improvements

- Hyperparameter Tuning
- Feature Engineering
- Compare multiple ML algorithms
- Deploy using Flask or Streamlit
- Real-time customer churn prediction

---

## 👨‍💻 Author

**Mathan R**

BCA Student | Machine Learning Enthusiast

GitHub: https://github.com/yourusername

---

## ⭐ Conclusion

This project demonstrates how Machine Learning can help banks predict customer churn. By identifying customers who are likely to leave, businesses can take proactive measures to improve customer satisfaction and retention.
