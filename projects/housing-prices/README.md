# 🏡 Housing Prices Predictor
*A neural network for real-estate price estimation using Kaggle’s House Prices dataset*

---

## 📘 Overview
This project builds a neural network capable of predicting the sale price of a house in USD using **81 numerical and categorical features** from the Kaggle dataset **House Prices – Advanced Regression Techniques**.

The project demonstrates:
- Data cleaning & preprocessing  
- Feature engineering and one-hot encoding  
- Missing-value imputation  
- Normalization  
- PyTorch model design  
- Training and evaluation  
- Visualization of results  

The final model achieves an **R² score of 0.97** on the test set.

---

## 📂 Dataset

Source:  
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

### Dataset characteristics:
- ~1,460 samples  
- 81 features  
- Target: `SalePrice`  
- Contains both numerical and categorical variables  
- Several features contain missing values  

---

## 🛠️ Preprocessing Pipeline

### ✔ Missing values
- Numerical → median imputation  
- Categorical → `"Missing"` placeholder  

### ✔ One-hot encoding
Converted all categorical features into binary indicator vectors.

### ✔ Normalization
Applied:

