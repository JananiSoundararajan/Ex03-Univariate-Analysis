# Ex03-Univariate-Analysis
# Aim
To read the given data and perform the univariate analysis with different types of plots.

# Explanation
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm
### Step 1
Read the given data.

### Step 2
Get the information about the data.

### Step 3
Remove the null values from the data.

### Step 4
Mention the datatypes from the data.

### Step 5
Count the values from the data.

### Step 6
Do plots like boxplots,countplot,distribution plot,histogram plot.


# PROGRAM
```
Developed by: Janani.S
Register Number: 212222230049
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib as plt
df=pd.read_csv("diabetes.csv")
```
# OUTPUT
### df.info()
![OUTPUT](diainfo.png)
### df.dtypes
![OUTPUT](dtypes.png)
### value_counts()
![OUTPUT](valuecounts.png)
### df.describe()
![OUTPUT](describe.png)
### boxplot
![OUTPUT](boxplot.png)
### countplot
![OUTPUT](countplot.png)
### ditribution plot
![OUTPUT](distplot.png)
### histplot
![OUTPUT](histplot.png)
### df.skew()
![OUTPUT](skew.png)
![OUTPUT](skewhist.png)
![OUTPUT](skewdist.png)
# RESULT
Thus the given data is read and performed univariate analysis with different types of plot.
