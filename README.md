# Titanic-Survival-Classification

## Internship Task(Data Science) – Task 1

### Author: Tashfah Ashraf 
---

## Task Objective

The objective of this task is to build a machine learning model to predict whether a passenger survived the Titanic disaster. The prediction is based on features such as Age, Gender, Ticket Class (Pclass), and Fare.

---

## Dataset

The dataset used is the classic Titanic dataset from Kaggle. It contains information about passengers on the Titanic, including whether they survived or not.

---

## Steps Completed

1. **Data Loading**  
   Loaded the dataset (`train.csv`) using Pandas.

2. **Data Cleaning & Preprocessing**  
   - Checked for missing values and filled missing `Age` values with the median age.  
   - Converted categorical `Sex` feature into numerical values (male = 1, female = 0).  
   - Selected relevant features: `Pclass`, `Sex`, `Age`, and `Fare`.

3. **Data Splitting**  
   Split the dataset into training and testing sets (80% train, 20% test).

4. **Model Training**  
   Trained a Random Forest Classifier on the training data.

5. **Model Evaluation**  
   Evaluated the model's performance using accuracy score, confusion matrix, and classification report.

6. **Comparison**  
   Trained a Logistic Regression model for performance comparison.

7. **Feature Importance**  
   Visualized the importance of features for the Random Forest model.

8. **Model Saving**  
   Saved the trained Random Forest model using `joblib` for future use.

---

## Results

- **Random Forest Accuracy:**
 <img width="391" height="697" alt="image" src="https://github.com/user-attachments/assets/8097d03c-b6b1-46b5-a72d-85a7f155d61f" />
  
- **Logistic Regression Accuracy:**  *0.8044692737430168*

The Random Forest model showed good performance in predicting survival, indicating that the chosen features are predictive. Further improvements can be achieved by hyperparameter tuning or using more features.

---

