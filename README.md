# SVM-Based-Stock-Market-Price-Prediction-and-Iris-Dataset-Classification
This project is an exploration of utilizing Support Vector Machines (SVM) to perform two distinct tasks: stock market price prediction and classification of the famous Iris dataset. SVM is a powerful machine learning algorithm known for its ability to handle complex, high-dimensional datasets and has shown promising results in various domains.


# Tools and Technologies used
1)Python
2)SKlearn-Support Vector Classifier

# Stock-Market-Prediction
In this part of the project, we aim to build a predictive model using SVM to forecast stock market prices. The dataset used for this task will consist of historical stock market data, including price, volume, and other relevant financial indicators.The Data Is stored in OHLC(Open, High, Low, Close)  format in a CSV file. Explanatory or independent variables are used to predict the value response variable. We will preprocess the data, engineer meaningful features, and perform exploratory data analysis to gain insights into the underlying patterns.
The target variable is the outcome which the machine learning model will predict based on the explanatory variables.If tomorrow’s price is greater than today’s price then we will buy the particular Stock else we will have no position in the. We will store +1 for a buy signal and 0 for a no position in y.We will use SVC() function from sklearn.svm.SVC library to create our classifier model using the fit() method on the training data set.We will compute the accuracy of the algorithm on the train and test the data set by comparing the actual values of the signal with the predicted values of the signal.
Data was chosen from Yahoo Finance

# Iris Dataset Classification
The Iris dataset consists of measurements of iris flowers, and the task is to categorize them into one of three species based on these measurements.The Iris dataset will be preprocessed and visualized to gain insights into the distribution and relationships between features.

# Dataset source
Reliance stock Dataset: Yahoo Finance
Iris Dataset: Kaggle
