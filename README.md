# Charlie Gottschalk — Data Science & Neural Network Portfolio

# 📘 Table of Contents
- [Introduction](#introduction)
- [Housing Prices Predictor](#housing-prices-predictor)
- [Diabetes Classification Model](#diabetes-classification-model)
- [Links & Contact Info](#links--contact-info)

---

# Introduction
Welcome to my data science and neural network portfolio. This repository highlights machine learning projects I’ve built using PyTorch and real-world datasets from Kaggle. Each project focuses on a clear objective—whether predicting home sale prices or assisting in medical diagnosis—and demonstrates my ability to design models, preprocess data, evaluate performance, and visualize results.  
More detailed writeups for each project will be available soon on standalone GitHub pages.

---

# Housing Prices Predictor
### [**Housing Prices Predictor**](#)  
This project builds a neural network capable of estimating the sale price of a house in USD using 81 numerical and categorical features. The model is trained on the well-known Kaggle dataset *House Prices – Advanced Regression Techniques*. The workflow includes one-hot encoding, imputation of missing data, normalization, model construction in PyTorch, and optimization with Adam and MSELoss.  
The final model performs competitively with an **R² score of 0.97** on test data, demonstrating strong predictive accuracy for real-estate valuation tasks.

<div align="center">
  <img src="https://github.com/charchar1245/Charlie_Portfolio/blob/main/images/HousingPrices_training.png?raw=true" 
       alt="Housing Prices Training Loss"
       width="600">
  <br>
  <em>Training Loss Curve for Housing Prices Model</em>
</div>

---

# Diabetes Classification Model
### [**Diabetes Classification Model**](#)  
Using a dataset of 100,000 patients with 9 clinical features, this neural network was developed to support diabetes diagnosis by predicting whether an individual is likely to have diabetes. Techniques such as dropout, `pos_weight`, and sigmoid-based probability outputs were used to address class imbalance and improve recall.  
The model achieves **60% precision, 89% recall, and a 70% F1 score**, making it particularly effective for identifying positive diabetes cases in a medical screening context.

<h3 align="center">Model Performance Visualizations</h3>

<div align="center">
  <table>
    <tr>
      <td align="center" style="padding: 10px;">
        <img src="https://github.com/charchar1245/Charlie_Portfolio/blob/main/images/diabetes_predictor_training.png?raw=true" alt="Training Loss" width="450">
        <br>
        <em>Training Loss per Epoch</em>
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://github.com/charchar1245/Charlie_Portfolio/blob/main/images/diabetes_predictor_confusion_matrix.png?raw=true" alt="Confusion Matrix" width="450">
        <br>
        <em>Confusion Matrix</em>
      </td>
    </tr>
  </table>
</div>

---

# Links & Contact Info
- [LinkedIn](#)
- [Blog](#)
- [Resume](#)
- [Kaggle](#)

