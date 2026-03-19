# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import pandas as pd.
<br>


### Step2
Read the csv file.
<br>

### Step3
Get the value of X and y variables
<br>


### Step4
Create the linear regression model and fit.
<br>

### Step5
Predict the CO2 emission of a car where the weight is 3300kg, and the volume is 1300cm cube.
<br>

## Program:
```
Developed By:AARTHI B
Register No:212225230001
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[["Volume","Weight"]]
y=df["CO2"]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))
```
## Output:

### Insert your output
![output](<Screenshot 2026-03-17 110420.png>)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
