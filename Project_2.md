# 2. Working with Callbacks


# Objective:
The objective of this project is to classify data into different categories using deep learning techniques. The project involves building four different models using different activation functions, optimizers, and initializers to analyze the training process and evaluate their performance. The project also involves implementing various callbacks, including custom callbacks to improve the model's accuracy.

# Data:
The data used in this project is available in the data.csv file, which can be downloaded from https://drive.google.com/file/d/15dCNcmKskcFVjs7R0ElQkR61Ex53uJpM/view.

# Methodology:
The project involves building four different models using various activation functions, optimizers, and initializers to classify the given data into different categories. The project also involves implementing custom callbacks to improve the model's accuracy and prevent overfitting. The model's performance is evaluated by analyzing the high-level statistics of the dataset, observations, and conclusion. The project also uses TensorBoard to analyze the model's training process and evaluate its performance.

# Step-wise approach:
1. Download the data from the given link.
2. Build four different models using different activation functions, optimizers, and initializers.
3. Implement custom callbacks to improve the model's accuracy and prevent overfitting.
4. Analyze the model's performance by evaluating high-level statistics of the dataset, observations, and conclusion.
5. Use TensorBoard to analyze the model's training process and evaluate its performance.

# High-level statistics of the dataset:
The dataset consists of 150,000 rows and 26 columns. Each row represents a customer transaction, and the columns represent various attributes of the transaction. The dataset has a class imbalance, with one class having significantly more samples than the other. The dataset's target variable is binary, with 0 representing one class and 1 representing the other class.

# Observations:
After analyzing the performance of the four models, it was observed that Model-3 performed the best, with an F1-score of 0.963 and AUC of 0.997. The model used the ReLU activation function, the SGD optimizer with momentum, and the he_uniform initializer. The custom callbacks implemented in the model helped improve its accuracy and prevent overfitting.

# Conclusion:
The project demonstrated the effectiveness of deep learning techniques in classifying data into different categories. The project also highlighted the importance of implementing custom callbacks to improve the model's accuracy and prevent overfitting. The project can be further extended by using more advanced deep learning techniques and exploring different activation functions, optimizers, and initializers.
