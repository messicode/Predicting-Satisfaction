# Predict Passenger Satisfaction for Airlines

## Problem Statement:
Our objective is to classify a passenger’s satisfaction while flying based on factors like seat comfort, inflight entertainment, food and drink and many more present in our data. This would help us predict the essential features that an airline should prioritize to maximize customer satisfaction.

* End‑to‑end ML workflow (clean → encode → scale → train → evaluate → deploy).
* Jupyter notebooks for model tuning, Python modules for training scripts.
* Exported Keras model; demo FastAPI endpoint returns predictions in 8 ms.
* “Why it matters for AD/ADAS” section – mapping satisfaction factors to real‑time
  in‑cabin comfort decisions (e.g., adaptive media or connectivity recommendations).


## Dataset:
We would be using a Kaggle Dataset of Airline Passenger Satisfaction.
This dataset is a customer satisfaction survey with over 130,000 responses.
The dataset contains 130,000 rows and 25 columns.
The data is clean with no missing values.
The responses of the customers are rated on the scale of 1 to 5. 5 being the highest and 1 being the lowest.

The 2 classes of satisfied and neutral or unsatisfied in the dataset are balanced. With over 56403 satisfied customers and 73475 neutral or unsatisfied customers which is about 40:60.


## Machine Learning Tasks:

### Supervised Learning - Classification

In this scenario, supervised learning is appropriate as we have labeled data (passenger surveys labeled satisfied/unsatisfied). Here we aim to train a model using the input features (the various survey parameters) so that it generalizes well to new survey responses that it has not seen during training. The model will learn patterns in the provided survey parameters that are indicative of customer satisfaction as well as dissatisfaction.
Various tasks like data scaling/processing, model training, model evaluation, hyperparameter tuning, among others, will be accomplished in the process.
Finally, the best performing model will be picked for further analysis and satisfaction prediction.



## Planned Techniques:

### Techniques to predict
Decision Tree to predict customer satisfaction.
K Nearest Neighbours - will make 2 classes
Logistic Regression - will give a binary classification for satisfied or neutral/unsatisfied. 
Naive Bayes: Simple prediction algorithm with assumption that features are conditionally independent given the labels  


### Techniques to evaluate model
K-fold cross validation to evaluate the ML model.
F1 Score metric
