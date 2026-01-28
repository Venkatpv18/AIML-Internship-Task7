#  Titanic Survival Prediction using Logistic Regression

##  Task Overview
This project is part of **Task 7 – AI & ML Internship**, focusing on **binary classification** using **Logistic Regression**.  
The goal is to predict whether a passenger survived the Titanic disaster based on selected features.

---

##  Dataset
- **Dataset Used:** Seaborn Titanic Dataset  
- **Source:** `seaborn.load_dataset('titanic')`  
- This dataset is used as an **alternative to the Kaggle Titanic dataset**, as permitted in the task instructions.

---

## Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Seaborn  
- Matplotlib  

---

##  Features Used
- `pclass` – Passenger class  
- `sex` – Gender  
- `age` – Age  
- `fare` – Ticket fare  
- `embarked` – Port of embarkation  

**Target Variable:**  
- `survived` (0 = No, 1 = Yes)

---

## Workflow
1. Loaded Titanic dataset using Seaborn
2. Selected important features
3. Handled missing values:
   - Age → Median
   - Embarked → Mode
4. Encoded categorical variables using **OneHotEncoder**
5. Scaled numerical features using **StandardScaler**
6. Split data into training and testing sets (stratified)
7. Trained a **Logistic Regression** model
8. Evaluated the model using multiple performance metrics

---

## Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- AUC Score

---

## Visualizations
- **Confusion Matrix Heatmap**
- **ROC Curve with AUC Score**

These visualizations help in understanding model performance more reliably.

---

## 📁 Project Structure
