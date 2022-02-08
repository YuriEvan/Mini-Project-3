### Mini-Project-3 (Machine Learning, using Python) Overview

This is a _Mini Group Project 3_ which consist of 5 members (Evan, Grace, Michelle, Desmond & Pauline). <br>

Roles for this Mini-Project-3 <br>
Evan - data prepration / model development & validation <br>
Grace - data prepration / model iterations <br>
Michelle - data prepration / documentation & presentation  <br>
Desmond - model iterations / documentation & presentation <br>
Pauline - model iterations / model development & validation <br>

#### Introduction - Major SEA Telecom Provider
- Providing telecom services to prepaid and postpaid customer segments combined with variety of product offers and plans


#### Business Problem
- Company's postpaid business of voice only plans is struggling to maintain its strong foothold in local market because of,
- Decline in overall customer base (high churn rate combined with low acquisition rate), leading to a decline in total market share
- High churn rate amongst customers leading to a revenue decline of ~500k USD every month
- 
#### Project objectives
_Business Objective_
- Reduce monthly customer churn by identifying high risk customers well in advance

_Hypothesis_
- Company CEO believes that existing models can predict churners precisely, but it's too late to take any retention actions, as customers usage have significantly declined by then

#### Mini Project 3 questions

1.Detect and resolve problems in the data (Missing value, Outliers, Unexpected value, etc.) <br>
i. How many customers had zero monthly revenue? <br> 
ii. How many columns have missing values percentage > 5%? <br>
iii. For columns, "UniqueSubs" and "DirectorAssistedCalls" remove outliers, if any <br>

2.Perform exploratory analysis to analyze customer churn <br>
i. Does customers with high overage minutes also have high revenue? <br>
ii. Does high number of active subscribers lead to low monthly revenue? <br>
iii. Does credit rating have an impact in churn rate? <br>

3.Create additional features to help predict churn <br>
i. Percent of current active subs over total subs <br>
ii. Percent of recurrent charge to monthly charge <br>
iii. Percent of overage minutes over total monthly minutes <br>

4.Build classification model to predict customer churn <br>
i. Build a simple logistic regression model to predict churn and evaluate model accuracy on test data set <br>
ii. Build Random Forest classifier to compare model accuracy over the logistic regression model <br>
iii. Identify most important features impacting churn (Model evaluation metrics to be used: GINI, AUC, Precision and Recall) <br>

5.Use the hold out data provided to predict churners using the best model identified in step 4 <br>

6.Bonus Question:Calculate lift chart and total monthly revenue saved by targeting top 10-20% of the customers using your best predictive model <br>

#### Mini Project 3 Answers

*Answers to the questions above, please click on the link below* <br>
[Click here to view code](https://github.com/YuriEvan/Mini-Project-3/blob/main/Mini_project_3%20(Group%208).ipynb)
