# Predicting Fracture Risk in Osteoporosis Patients
This project aimed to develop a model that could accurately predict whether a patient with osteoporosis is at risk of experiencing a fracture. The project utilized two classification algorithms, K-Nearest Neighbors (KNN) and Logistic Regression, to determine which model was better suited for the prediction task.


The dataset included clinical data for 169 osteoporosis patients, including age, gender, bone mineral density (BMD), and several other relevant factors. 

## Data Preparation:
Explore the data set to identify any missing values or outliers.
Preprocess the data by encoding categorical variables using one-hot encoding, scaling numerical variables, and splitting the data into training and testing sets. Also, normalized the data.

## Model Building:
Used Random Sampling to train both models on the training set and evaluate their performance on the testing set.
Built a logistic regression model & KNN model using scikit-learn.


## Model Comparison:
The models were compared based on several evaluation metrics, including accuracy, precision, recall, and F1 score.

* Comparing the KNN algorithm's performance with logistic regression,  logistic regression achieved an accuracy of 0.80. Therefore, KNN (when k = 7, accuracy score = 0.88) performed better than logistic regression in terms of classification accuracy on this dataset.

* It was also found that the KNN model performed better than the Logistic Regression model in identifying patients who were at high risk of experiencing a fracture. The KNN model had a higher recall score, indicating that it was better at correctly identifying patients who had a fracture.
