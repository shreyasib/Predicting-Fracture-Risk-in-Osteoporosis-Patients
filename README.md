# Predicting Fracture Risk in Osteoporosis Patients

## Data Preparation:
Explore the data set to identify any missing values or outliers.
Preprocess the data by encoding categorical variables using one-hot encoding, scaling numerical variables, and splitting the data into training and testing sets. Also, normalized the data.

## Model Building:
Built a logistic regression model & KNN model using scikit-learn.
Used Random Sampling to train both models on the training set and evaluate their performance on the testing set.

## Performance Evaluation:
Evaluated the models using classification metrics such as accuracy, precision, recall, F1 score, and area under the ROC curve (AUC-ROC).
Use cross-validation to assess the generalization performance of the models.

## Model Comparison:
Comparing the KNN algorithm's performance with logistic regression,  logistic regression achieved an accuracy of 0.80. Therefore, KNN (when k = 7, accuracy score = 0.88) performed better than logistic regression in terms of classification accuracy on this dataset.
