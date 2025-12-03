# Charlie_Gottschalk_Portfolio
Data Science &amp; Neural Network Portfolio

# Project 1: Neural Network Housing Prices Estimator: Project Overview
* Created a tool that can estimate a houses sale price in USD using 81 different features to assist sellers in setting an appropriate price
* Uses data from the Kaggle competition dataset, "House Prices - Advanced Regression Techniques" to predict estimates
* Pre-processes data using One-Hot Encoding of categorical columns and mean value filling of missing values
* Optimized, simple neural network built using the PyTorch neural network library and tools like the Adam optimizer and the Mean Squared Error Loss function
* Performs accurately on test data with a R^2 value of .97

# Project 2: Neural Network Diabetes Classifier: Project Overview
* Created a tool that, using 9 different features for 100,000 patients, assists doctors in diagnosing diabetes
* Uses medical data from Kaggle dataset to make predictions
* Uses a simple neural network with techniques such as neuron dropout, pos_weight, and the sigmoid function (using PyTorch)
* Overall functionality measured with 60% precision, 89% recall, and 70% F1 score

<h3 align="center">Model Performance Visualizations</h3>

<div align="center">
  <table>
    <tr>
      <td align="center" style="padding: 10px;">
        <img src="https://github.com/charchar1245/Charlie_Portfolio/blob/main/images/diabetes_predictor_training.png" alt="Training Loss" width="450">
        <br>
        <em>Training Loss per Epoch</em>
      </td>
      <td align="center" style="padding: 10px;">
        <img src="https://github.com/charchar1245/Charlie_Portfolio/blob/main/images/diabetes_predictor_confusion_matrix.png" alt="Confusion Matrix" width="450">
        <br>
        <em>Confusion Matrix</em>
      </td>
    </tr>
  </table>
</div>
