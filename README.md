# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Load and Prepare Data:
Read data
Select features and target
### Step2
Create and Train Model

### Step3
Make Predictions
### Step4
Print coefficients and intercept:
Display model's learned coefficients (regr.coef_) and intercept (regr.intercept_)

### Step5
Predict for new data:
Use regr.predict([[3300, 1300]]) to predict CO2 emission for a car with weight 3300 and volume 1300
Print the predicted amount
## Program:
```
#Implementation of Multivariate Linear Regression
#Developed by : P PARTHIBAN
#Registration name:
import pandas as pd
from sklearn import linear_model

df=pd. read_csv('cars . csv')
a-df[['Weight, Volume' ]]
b=df[['c02 ']]
regr=linear_model. LinearRegression ()
regr. fit(a, b)
print("coefficient", regr. coef_)
print ("Intercept:", regr.intercept_)
print ("Amount:", regr.predict ([[3300,1300]]) )





```
## Output:
![image](https://github.com/23007965/Multivariate-Linear-Regression/assets/138971238/4ec2b2a9-174a-4a0a-9671-72e8fa95984c)



![WhatsApp Image 2023-12-31 at 23 53 54_deff7b1e](https://github.com/23007965/Multivariate-Linear-Regression/assets/138971238/1cbd28ca-c5ea-497e-bc56-a9dbbd1ce17e)


![WhatsApp Image 2023-12-31 at 23 53 53_a334036c](https://github.com/23007965/Multivariate-Linear-Regression/assets/138971238/dff71da2-82f1-4be0-8576-3c25c54438f1)



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
