# Obseity-data-analysis
This repository contains a DNN model to predict obesity levels (Normal Weight, Obesity Type I-III, Insufficient Weight) based on features like age, gender, height, and weight. The model uses ReLU activation in hidden layers and Softmax for output. It achieved 97.6% training accuracy and 87.01% validation accuracy.
Obesity Classification Using DNN
This repository contains a Deep Neural Network (DNN) model for predicting obesity levels based on features like age, gender, height, weight, and lifestyle factors. The model classifies into five categories: Normal Weight, Obesity Type I, Obesity Type II, Obesity Type III, and Insufficient Weight.

Features:
Data Preprocessing: Categorical variables are encoded, and numerical features are scaled.
Model Architecture: A Sequential DNN with ReLU activation for hidden layers and Softmax for output.
Optimization: Adam optimizer with a learning rate of 0.001 and sparse categorical cross-entropy loss.
Performance: Achieved 97.60% training accuracy and 87.01% validation accuracy.
Requirements:
Python 3.x
TensorFlow / Keras
Pandas, NumPy, scikit-learn
How to Use:
Clone this repository.
Install the necessary dependencies.
Train the model on your own dataset or use the provided dataset for reproduction.
Adapt the model for similar multi-class classification tasks.
License:
This project is licensed under the MIT License.

