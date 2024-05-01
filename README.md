# Predicting Fracture Risk in Osteoporosis Patients
This project aimed to develop a model that could accurately predict whether a patient with osteoporosis is at risk of experiencing a fracture. The project utilized two classification algorithms, K-Nearest Neighbors (KNN) and Logistic Regression, to determine which model was better suited for the prediction task.


The dataset included clinical data for 169 osteoporosis patients, including age, gender, bone mineral density (BMD), and several other relevant factors. 

## Data Preparation:
Explore the data set to identify any missing values or outliers.
Preprocess the data by encoding categorical variables using one-hot encoding, scaling numerical variables, and splitting the data into training and testing sets. Also, normalized the data.

## Model Building:
Used Random Sampling to train both models on the training set and evaluate their performance on the testing set.
Built a logistic regression model, KNN model & Random Forrest using scikit-learn.


## Model Comparison:
The models were compared based on several evaluation metrics.

## 1. In terms of Accuracy Score

* RF (10 Trees): 0.99
* KNN(when k=7): 0.88
* LR: 0.80

 Therefore, Random Forrest with 10 trees performed better than LR & KNN in terms of accuracy score.

## 2. In terms of classfications:

#### Correct Classifications:

* RF (10 Trees): 99 correct predictions
* KNN:88 
* LR: 80


#### Incorrect/Missclassifications:

* RN (10 Trees): 1 incorrect predictions
* KNN: 12 
* LR: 20

So, Random Forrest with 10 trees has more correct classifications & less missclssifications compared to LR & KNN. Hence, Random Forrest is the better model!
