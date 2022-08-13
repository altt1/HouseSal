# HouseSal
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import seaborn as sns
from sklearn.pipeline import Pipeline
from sklearn.preprocessing import StandardScaler,PolynomialFeatures
from sklearn.linear_model import LinearRegression
matplotlib inline

#Module 1
df=pd.DataFrame(data)
df.head()
df.dtypes()


#Module 2
x_data=df.drop([“id”],[“unnamed: 0”], axis=1)
df.describe(x_data)


#Module 3
