# ComparingClassifiers

Required Assignment 17.1: Comparing Classifiers

Overview: In this practical application, my goal is to compare the performance of the classifiers we encountered in this section, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. I will utilize a dataset related to marketing bank products over the telephone.

# Understanding the Data

The dataset collected is related to 17 campaigns.

Understanding the Task
After examining the description and data, your goal now is to clearly state the Business Objective of the task. State the objective below.
This dataset was provided for a Portugese banking as a collection of multiple marketing campaign results.

From a business objective, the task of this Machine Learning project is to determine which factors could lead to a higher success rates to sign up for the long term deposit product.

feature_cols = ['job', 'marital', 'education', 'default', 'housing','loan', 'contact','month','day_of_week','poutcome']

X=df[feature_cols]
y=df['deposit']

A Baseline Model
Before we build our first model, we want to establish a baseline. What is the baseline performance that our classifier should aim to beat?
