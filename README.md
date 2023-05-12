# PREDICTING SUCCESS FOR NBA PLAYERS AFTER 5 YEARS

# Problem Statement:
Young NBA players face a number of challenges and obstacles on their path to a successful
future in the league. There are times when a very exciting basketball talent comes to the league
and after some time the player vanishes from the scene, and the experts are left to debate the
reason why this is the case. Why are some players successful and some are not? There are
several aspects that might help identify the root cause of this eventual fallout. The dataset we
have chosen is a record of statistics of several rookie NBA players throughout their first season.
Given these sets of features we want to predict whether the player would still be playing in
the NBA 5 years later (1 -indicating he will play or 0- indicating he won’t play).

# Dataset:
The dataset comprises of 17 features in form of columns, consisting of key attributes such as:
Mean number of points scored, mean number of field goals scored, mean number of field goals
attempted, mean number of 3-point shots made, mean number of 3-point shots attempted, etc.,
out of which we may opt to use the essential features only, during implementation. We can use
PCA, correlation and L1 Regularization for feature reduction.

# Source of Dataset:
1. https://www.kaggle.com/code/tombutton/lesson-8-predicting-success-for-nba-players/input
2. https://www.nba.com
- Final compiled data can be found [here](https://www.kaggle.com/datasets/kaustubhlohani/nba-rookie-data-1950-2018)

# Implementation Strategy and algorithms used:
The following are the models implemented:
1. Naïve Bayes
2. Decision Trees
3. Logistic Regression with Grid Search CV
4. Artificial Neural Networks
5. K-nearest neighbor with Grid Search CV
6. Random Forest with Randomized Search CV
7. Support Vector Machine with Grid Search CV

# Model metrics and Evaluation:
1. Accuracy
2. F-1 Score
3. Precision
4. Recall
5. Confusion matrix
6. AUC-ROC Curve