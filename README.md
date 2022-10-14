# Linear-Regression-Presentation
Team - Akul Bajaj, Andres Martinez Tobon, Bharadwaj Yadav Allu
 
Linear Regression study session is a skit designed by three students to replicate issues faced when trying to complete multiple linear regression on a project.
 
Roles:
* Student 1: Akul Bajaj
* Student 2: Andres Martinez Tobon
* TA: Bharadwaj Yadav Allu
 
Initially, Student 2 (Andres) asked Student 1 (Akul) what he thought about trying linear regression on time series data. Akul then explained that linear regression would be difficult on a time series data set. Akul constructed an example using DailyDelhiClimate.csv. He graphed mean temp on the Y-axis and time in the form of date on the X-axis. Akul then went on to explain why time series data is not compatible with linear regression. These reasons include:
* A given observation will influence following observations in time series
* Time series has a cyclical component
* Dependence of errors (residuals are not random) exists in time series
* Time series data violates the assumption of independent errors
 
Following this time series explanation, Akul went on to ask Andres: what should he do when his data is violating several assumptions? Andres then went on to explain how transformations can twist data to make it accommodate the assumptions. Some of the assumptions Andres attempted to troubleshoot include: 
1. Normality
2. Homoscedasticity
3. Linearity
 
Andres demonstrated different types of transformations such as square root transformations and logarithmic transformations. He further explained that transformations can be applied to the dependent variable, the independent variables, or both types of variables. Additionally, he discussed that some transformations are linear and some are non-linear. Using kc_house_data.csv he plotted distribution plots to demonstrate how effective the transformations were.
 
Now, after transformations, Akul pointed out an issue in the model summaries of the credit.csv dataset. He inquired why the studentized t statistic of predictor ‘rating’ changed so drastically after removing predictor ‘limit’. TA Allu jumped in to explain what was going on here. He claimed that the situation seemed like a case of multicollinearity. Initially, Allu checked his diagnosis through a heat map and VIF scores. Both these methods demonstrated high correlation and multicollinearity between rating and limit. Allu further emphasized that solutions to multicollinearity problems like such include: dropping or combining the predictors. In the credit.csv example combination of the predictors was not possible because they were of a different scale. 
 
The group concluded their skit by explaining and inquiring about the relevance of linear regression in real-world scenarios. TA Allu highlighted the benefits and pitfalls of linear regression, like high interpretability and sensitivity to outliers respectively. We hope our presentation and code help you troubleshoot when conducting linear regression analysis.

