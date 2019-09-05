# Finding Donors for _CharityML_
This is a Supervised Learning project for Udacity’s “Machine Learning – Introduction” nanodegree program. It uses machine learning methods to model individuals’ income using data collected by the 1994 U.S. Census. The goal is to help a fictional charity organization that wants to identify people who are likely to donate.

The data set comes from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income), and it was donated by Ron Kohavi and Barry Becker and published in their article _"Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid"_, located [here]( https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf). The dataset used here has some small changes: the 'fnlwgt' feature, and records with missing or ill-formatted entries, were removed.

The independent variables are: age, working class, education level, number of educational years completed, marital status, occupation, relationship status, race, sex, capital gains, capital losses, hours per week worked, and native country. The (binary) dependent variable is income class: <=50K or >50K.

In this exercise I explored the data, prepared the data, evaluated model performance, improved the results, and determined feature importance. The supervised learning models I used were DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, and AdaBoostClassifier.

I used Python 3.6.9.

This project was reviewed by a Udacity reviewer.
