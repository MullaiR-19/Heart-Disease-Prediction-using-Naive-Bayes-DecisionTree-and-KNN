##Heart Attack Prediction using Naive Bayes DecisionTree KNN 

Heart Attack is a significant health problem globally and is a leading cause of death. Machine learning algorithms can be used to predict 
the likelihood of heart disease, which can help doctors make better treatment decisions. 
In this project, I have implement three machine learning algorithms to predict the chance of heart disease: Naive Bayes, Decision Tree, and 
K-Nearest Neighbors (KNN).

The dataset used for this project is the Cleveland Heart Disease dataset, which contains 11 attributes, including patient age,
medical history, and laboratory test results.

We then train and evaluate each of the three algorithms compare the performance of each algorithm in terms of accuracy, precision, recall, and F1 score.

The Naive Bayes algorithm assumes that each feature is independent of the others, and calculates the likelihood of each feature given the class. 
The Decision Tree algorithm recursively splits the data based on the feature that provides the most information gain, until a leaf node is reached. 
The KNN algorithm classifies an instance by finding the k nearest neighbors in the training data and taking the majority class.

The results show that all three algorithms perform reasonably well in predicting the chance of heart disease, with Decision Tree achieving the 
highest accuracy. However, further optimization is needed to improve the performance of each algorithm.

Naive Bayes came out with accuracy of : 84.7%
Decision Tree show accuracy upto: 85.6% (Using Gini critaion)
and K-Nearest Neighbors have accuracy of: 70.8% (neighbors value at 5)