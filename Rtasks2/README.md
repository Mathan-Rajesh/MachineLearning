# Online Shoppers Purchasing Intention Prediction

## Project Overview
This project predicts whether an online visitor will generate revenue (make a purchase) based on their browsing behavior using Machine Learning. The dataset contains information about user sessions, page visits, browsing duration, visitor type, operating system, browser, and other session-related features.

---

## Dataset Information

**Target Variable:**
- Revenue
  - True – Customer made a purchase.
  - False – Customer did not make a purchase.

**Input Features:**
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

---

## Objective

To build a Machine Learning classification model that predicts whether a customer will complete a purchase during an online shopping session.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## Machine Learning Algorithm

- Random Forest Classifier

---

## Project Workflow

### Step 1: Import Libraries
Import all required Python libraries.

### Step 2: Load Dataset
Read the dataset using Pandas.

### Step 3: Data Preprocessing
- Remove unnecessary spaces from column names.
- Encode categorical features using Label Encoder.
- Split features and target variable.

### Step 4: Split Dataset
Split the dataset into training and testing sets using an 80:20 ratio.

### Step 5: Train the Model
Train a Random Forest Classifier using the training data.

### Step 6: Make Predictions
Predict the Revenue value for the testing dataset.

### Step 7: Evaluate Model
Evaluate the model using:
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Performance Metrics

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Expected Accuracy

Using the Random Forest Classifier, the model generally achieves an accuracy of approximately **89%–91%**, depending on the train-test split and random state.

---

## Project Structure

```
Online_Shoppers_Project/
│
├── online_shoppers_intention.csv
├── online_shoppers_prediction.ipynb
├── README.md
```

---

## Future Enhancements

- Hyperparameter tuning
- Cross-validation
- XGBoost Classifier
- Feature Importance Analysis
- Model Deployment using Flask or Streamlit

---

## Conclusion

This project demonstrates how Machine Learning can analyze customer browsing behavior and accurately predict purchasing intention. Such prediction models help e-commerce businesses improve marketing strategies, customer targeting, and conversion rates.

---

## Author

**Mathan R**

Bachelor of Computer Applications (BCA)

Kamaraj College

2027 Batch
