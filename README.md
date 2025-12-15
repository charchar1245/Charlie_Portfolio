# Charlie Gottschalk — Data Science & Neural Network Portfolio

# 📘 Table of Contents
- [Introduction](#introduction)
- [Cat vs. Dog Image Classifier](#cat-vs-dog-image-classifier)
- [Housing Prices Predictor](#housing-prices-predictor)
- [Diabetes Classification Model](#diabetes-classification-model)
- [Links & Contact Info](#links--contact-info)

---

# Introduction
My name is Charlie Gottschalk, I'm a third-year Computer Science student at the University of Georgia with an area of emphasis in Data Science and Artificial Intelligence. This repository highlights machine learning projects I’ve built using PyTorch and real-world datasets from Kaggle. Each project focuses on a clear objective and demonstrates my ability to design models, preprocess data, evaluate performance, and visualize results. 

On the bottom of this page you can find a link to my LinkedIn page, my blog that documents my educational journey into the world of Neural Networks and other various Machine Learning techniques to gain additional context for all of my projects and to see how I've progressed in my knowledge and ability. 
You can also find a link to my resume and my Kaggle profile as well.

---

# [Cat vs. Dog Image Classifier](projects/catdog-classifier)
This project deploys a Convolutional Neural Network (CNN) made in PyTorch to be able to recognize any provided 128x128 pixel image as either a cat or a dog. It is trained with over 500 images in each category, and the images used for training are modified by rotation, modifying colors,
and flipped in order to challenge the model into memorizing general patterns that cats and dogs respectively share over specific noise in order to reduce overfitting of data and make the model more robust. The model achieves 78% accuracy on the validation set.

---

# [Student Course Failure Risk Classification](#)
This project emplys a data pipeline on over 100,000 students' online course data in order to predict their risk of failing an online course theat they're enrolled in. The data pipeline consists of documented Exploratory Data Analysis, Pre-processing, Model Training & Cross-Validation, hyper-parameter tuning, and some final evaluations and conclusions. Logistic Regression was found to be the best performing model for the task after performing threshold tuning, outcompeting Random Forest and Gradient Boosting models.
Originally started as a binary classification task (will the student pass or fail?) but was modified into a classification task where each student is determined to be either high-risk, medium-risk, or low-risk.


# [Housing Prices Predictor](projects/housing-prices)
This project builds a neural network capable of estimating the sale price of a house in USD using 81 numerical and categorical features. The model is trained on the well-known Kaggle dataset *House Prices – Advanced Regression Techniques*. The workflow includes one-hot encoding, imputation of missing data, normalization, model construction in PyTorch, and optimization with Adam and MSELoss.  
The final model performs competitively with an **R² score of 0.97** on test data, demonstrating strong predictive accuracy for real-estate valuation tasks.

---

# [Diabetes Classification Model](projects/diabetes-classifier)
Using a dataset of 100,000 patients with 9 clinical features, this neural network was developed to support diabetes diagnosis by predicting whether an individual is likely to have diabetes. Techniques such as dropout, `pos_weight`, and sigmoid-based probability outputs were used to address class imbalance and improve recall.  
The model achieves **60% precision, 89% recall, and a 70% F1 score**, making it particularly effective for identifying positive diabetes cases in a medical screening context.

---

# Links & Contact Info
- [LinkedIn](https://www.linkedin.com/in/charlesgottschalkacc/)
- [Blog](https://charchar1245.github.io/charlie-blog/index.html)
- [Resume](#)
- [Kaggle](https://www.kaggle.com/charliegottschalk)
