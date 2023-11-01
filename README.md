# Insurance-Premium-Prediction

Examine the data of a health insurance company with the goal of forecasting future insurance
claims and pinpointing the factors contributing to increased healthcare expenses. The dataset
contains information on 1,338 policyholders, encompassing 7 attributes that detail their health
and demographic characteristics, such as age, gender, BMI, and smoking habits. Our target
variable for prediction is the total claim amount, which represents the charges billed to the
insurance provider. To enhance the precision of our cost predictions, I will construct separate
models for each of the company's policyholder regions: Southwest, Southeast, Northwest, and
Northeast.


# Methodology:
To address the potential influences of two independent variables, such as smoking status and BMI,
on healthcare costs, I intend to enhance the models by introducing interaction terms and
incorporating second-order polynomial features. This augmentation will involve incorporating
squared terms for each variable within the model and including interaction terms that capture
relationships between pairs of features.
In terms of the beneficiary distribution across the four regions, there is a relatively even
distribution, with each region containing between 324 and 364 beneficiaries. To achieve more
precise cost predictions for future insurance claims, I plan to construct distinct models for each
region. This process will begin with data segmentation by region, followed by the creation of
individual training and testing datasets. My approach will encompass a variety of regression
models, including Linear Regression, K-Nearest Neighbours, Support Vector Machines, and
Gradient Boosting, to forecast forthcoming insurance costs. I will employ hyperparameter tuning
through cross-validation and subsequently assess the model performance on the reserved test
dataset.
