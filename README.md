# Correlation and Regression for Data Analysis
# Aim : 

To analyse given data using  coeffificient of correlation and regression line.
![image](https://user-images.githubusercontent.com/104613195/168224136-d6b64e64-7d3d-4775-9337-c8f96fe41f2d.png)


# Software required :  

Python

# Theory:

Correlation describes the strength of an association between two variables, and is completely symmetrical, the correlation between A and B is the same as the correlation between B and A. However, if the two variables are related it means that when one changes by a certain amount the other changes on an average by a certain amount.  

If y represents the dependent variable and x the independent variable, this relationship is described as the regression of y on x. The relationship can be represented by a simple equation called the regression equation. The regression equation representing how much y changes with any given change of x can be used to construct a regression line on a scatter diagram, and in the simplest case this is assumed to be a straight line.

# Procedure :

![image](https://user-images.githubusercontent.com/104613195/168225866-ac8f6610-bdc3-4ac2-a24e-2b24ba08e189.png)

# Program

```python

# Developed by
# Register Number: 212220230049
# Name: P.Suganya

import math
import numpy as np
x=[25, 28, 35, 32, 31, 36, 29, 38, 34, 32]
y=[43, 46, 49, 41, 36, 32, 31, 30, 33, 39]
sx=0
sy=0
sxy=0
sx2=0
sy2=0
for i in range(0,10):
    sx=sx+x[i]
    sy=sy+y[i]
    sxy=sxy+x[i]*y[i]
    sx2=sx2+x[i]**2
    sy2=sy2+y[i]**2
    N=10
r=(N*sxy-sx*sy)/(math.sqrt(N*sx2-sx**2)*math.sqrt(N*sy2-sy**2))
print("The Correlation Coefficient is %0.3f"%r)

```
# Output : 


# Result:
