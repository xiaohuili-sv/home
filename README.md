#  CAPSTONE PROJECT: EDA
## Xiaohui Li

This is Exploratory Data Analysis (EDA) of  final capstone project.  Advanced Machine Learning techniques were used to predict Credit card fraud.\
Dataset is from Kaggle https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

I explored initial data analysis and base model (Logistic Regression) prediction on the dataset.

why I chose this project?\
Global credit card fraud losses are massive and rising, reaching over $34 billion annually in 2023 with projections to reach $48.5 billion by 2034\

![distribution](./images/09-Confusion-Matrix-Logistic-Regression.png)

## Summary of Losgistic Regress Base Model
with a total of 56962 test samples, the matrix shows a highly imbalanced dataset with "0 - non-fraud" class predicted with high accuracy but the "1 - fraud" class is more difficult for the Logistic Regression model to capture.

True Negative (56,864): the modelcorrectly identified majority of the "0 - non-fraud" class.\
True Positive (55): The model correctly identified 55 instances of the target class.\
False Positive (10): the model predicted the target class when it was not there (Type I error).\
False Negative (43): the model missed 43 actual cases of target class(Type II error).

Precision (85%): when the model predicts "positive", it is right for about 85% of times.\
Recall (56%): the model only caught 56% of all actual "Positive" cases.\
F1-score (67%), this is the balance between precision and recall. A score of 0.67 suggests there is room to improve the model's ability to find the minority class without increacing false alarm.

For the final Capstone project, I plan to use additional sophestic models:
Decision Trees, Random Forest, Support Vector Machine, Neural Networks, Gradient boost models, Anomaly Detection etc.\

Evaluation method : accuracy, precision, recall, F1-score, PR AUC.
