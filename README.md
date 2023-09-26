# Covid-Awareness-and-Cases-in-Ohio
Covid-19 Awareness and Covid-19 Cases in Ohio
The data that we used for training had 3141 rows
and we had to predict the number of cases for the test data
which contained 7331 rows. After we combined the data, we
observed that there were 119 rows or days for each county
out of which some were in test data that had to be predicted.
We approached the problem in two ways: first, is a machine
learning model and second is a rule-based approach, where
we have used the observations from the data to predict the
cases in the test data. We have explained more about this in
the methods section. Since there were 144 columns in the data,
feature engineering was the most important part of the modelling,
for which we chose Correlation Analysis and Recursive Feature
Elimination. In total, we used 11 features. We had to predict the
number of cases in the county on certain days given the features.
We realized that it’s a regression problem and approached the
problem using regression-based algorithms. For training the data,
we tried several methods like Random Forest, Decision trees and
XG Boosting of which we got the best results for decision trees
with an R2 score of 0.98 on the training data. Both methods gave
us similar R2 scores on the test data. However, the rule-based
approach gave slightly better results than the machine learning
model.
