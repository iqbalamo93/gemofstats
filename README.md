# Gemofstats
This is one stop revison of stats

## Part 1: GENERALISED LINEAR  MODEL

Difference between  GLM AND Linear regression 
| No |  Linear Regression  | GLM |
|:-----:|:--------:|:------:|
| Inception   |  1809: By Gauss  | 1972: Nelder & Wedderburn  |
| Observations   | Y's or target observations are independent of each other. |The data  are independently distributed, i.e., cases are independent|
||Observations are from normal distribution Yi~N(µ,σ²)|Y's are from any exponential family distribution|
||Model is linear in nature|link function is used to get Y.A GLM does NOT assume a linear relationship between the response variable and the explanatory variables, but it does assume a linear relationship between the transformed expected response in terms of the link function and the explanatory variables; e.g., for binary logistic regression|
|Errors/Residuals|normally distributed|Errors need to be independent but NOT normally distributed.|
|Other| Assumes linear relationship betweeb Y and X||
|| Works better with continous response varaibles| Can also model discreate|
||![image](https://user-images.githubusercontent.com/32023419/213543774-67e5fa77-f948-46ab-b840-6af11edff039.png)| ![image](https://user-images.githubusercontent.com/32023419/213536545-d0d014d6-535d-4923-a529-e225d4ba28ed.png) |

> linear model/s is a special case of a generalized linear model (GLM).As, Normal distribution is also a exponential distibution.

## Poisson Distribution

* for x >= 0,1,2...idcreate in nature
