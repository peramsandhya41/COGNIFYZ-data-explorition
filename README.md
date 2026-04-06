# 🤖 Predictive Modeling - Restaurant Rating Prediction

This project focuses on building machine learning models to predict the **aggregate rating of restaurants** based on various features from the dataset.

---

## 📌 Objective

The goal is to develop regression models that can accurately predict restaurant ratings using features such as cost, votes, and service availability.

---

## 📂 Dataset Features Used

The following features were selected for building the model:

- Average Cost for Two
- Price Range
- Votes
- Has Table Booking (converted to numeric)
- Has Online Delivery (converted to numeric)

Target Variable:
- Aggregate Rating

---

## ⚙️ Data Preprocessing

- Removed missing values from the dataset
- Converted categorical variables:
  - Yes → 1  
  - No → 0  
- Selected relevant features for model training

---

## 🔀 Train-Test Split

The dataset was divided into:
- 80% Training Data  
- 20% Testing Data  

---

## 🤖 Models Used

### 1. Linear Regression
- Simple baseline model
- Assumes linear relationship between features and target

---

### 2. Decision Tree Regressor
- Captures non-linear relationships
- Splits data based on feature importance

---

### 3. Random Forest Regressor
- Ensemble model (multiple decision trees)
- Provides better accuracy and stability

---

## 📊 Evaluation Metrics

The models were evaluated using:

- RMSE (Root Mean Squared Error)
- R² Score (Coefficient of Determination)

---

## 📈 Results

- Linear Regression provided a basic prediction performance  
- Decision Tree improved non-linear predictions  
- Random Forest performed the best with:
  - Lower RMSE  
  - Higher R² Score  

---

## 💡 Conclusion

The Random Forest model proved to be the most effective for predicting restaurant ratings. This indicates that ensemble learning methods can better capture complex relationships in the dataset.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

---
