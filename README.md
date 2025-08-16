# 🚢 Titanic Survival Classification

## 📌 Author  
👩‍💻 **Tashfah Ashraf**  
*Intern – ARCH TECHNOLOGIES*  
##  Skills:
**Data Science, Machine Learning, Python, Pandas, Scikit-Learn **

---

## 📌 Project Overview
This project focuses on building a **machine learning model** using the **Titanic dataset** to predict whether a passenger survived the Titanic disaster.  
The dataset includes passenger information such as **age, gender, ticket class, and fare**.  

The task involves:  
- Cleaning and preprocessing the dataset  
- Building a classification model  
- Evaluating the model’s performance  

---

## 📊 Dataset
The dataset used is the **Titanic dataset (`train.csv`)**, which contains:  
- Passenger features (`Pclass`, `Sex`, `Age`, `Fare`, etc.)  
- Target variable: **Survived (0 = No, 1 = Yes)**  

---

## 🛠️ Steps Performed

### 1. Data Loading
- Loaded the Titanic dataset using `pandas`.

### 2. Data Cleaning
- Handled missing values:  
  - Filled missing `Age` values with the **median**.  

### 3. Feature Encoding
- Converted **Sex** column into numeric:  
  - Male = 1  
  - Female = 0  

### 4. Feature Selection
Selected the following features for prediction:  
- `Pclass`, `Sex`, `Age`, `Fare`  

### 5. Train-Test Split
- Split dataset into **80% training** and **20% testing**.  

### 6. Model Training
- **Random Forest Classifier** trained on the dataset.  

### 7. Model Evaluation
- Evaluated using:  
  - Accuracy  
  - Confusion Matrix  
  - Classification Report  

### 8. Feature Importance
- Visualized feature importance using bar chart.  

### 9. Logistic Regression (Comparison)
- Trained Logistic Regression model for comparison.  

### 10. Save Model
- Saved trained Random Forest model using `joblib`.  

---

## 📈 Results
- **Random Forest Classifier** achieved good accuracy.  
- **Logistic Regression** also tested for comparison.  
- **Feature Importance** showed that `Sex` and `Fare` are strong predictors of survival.  

---

## ⚡ Possible Improvements
- Add **Naïve Baseline** (e.g., predict all “Not Survived” for comparison).  
- Perform **EDA (Exploratory Data Analysis)** with survival rates by class, gender, etc.  
- Handle missing values in `Embarked`.  
- Try other models like **XGBoost, SVM, KNN** for comparison.  

---

## 📂 Project Files
- `Titanic_Survival_Classification.ipynb` → Main notebook  
- `train.csv` → Titanic dataset  
- `titanic_model.pkl` → Saved Random Forest model  

---

## 🚀 Conclusion
This project successfully demonstrates how to:  
- Preprocess real-world data  
- Build and evaluate ML classification models  
- Compare different algorithms (Random Forest vs Logistic Regression)  
- Save trained models for deployment  

The **Random Forest model** performed well, and the workflow can be extended with more features and advanced models.  
