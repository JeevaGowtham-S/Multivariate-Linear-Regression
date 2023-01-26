# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1
Open command prompt and activate conda, then open jupyter notebook
<br>

## Step2
Open a new cell Type the program
<br>

## Step3
Type the program
<br>

## Step4
Upload the csv file in the jupyter notebook
<br>

## Step5
Run the program
<br>

## Program:
```python
DEVELOPED BY: JEEVAGOWTHAM S
REFERENCE NO : 22008760
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars.csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print("Predicted CO2 for the corresponding weight and volume",predictedCO2)







```
## Output:

![Screenshot from 2023-01-26 13-49-16](https://user-images.githubusercontent.com/118042624/214788142-4caa7b40-bdd6-43f5-8fcd-9c32aa343b98.png)


<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
