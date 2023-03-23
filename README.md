# Customer-Data-Analysis
An Analysis and visualisation of customer data set 
# EDA-on-deaths-caused-due-to-various-factors-in-the-world
exploratory data analysis on deaths caused due to various factors in the world from 1990 to 2019

#### Table of Contents
  * 
  * 
  *

## Loading Libraries
```python
#importing necessary libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```
## Loading the dataset
```python
df = pd.read_csv("D:/Analytics/Datasets/Customer Data/Customers.csv")
```

## extracting first-five rows
```python
df.head()
```
```
CustomerID	Gender	Age	Annual Income ($)	Spending Score (1-100)	Profession	Work Experience	Family Size
0	1	Male	19	15000	39	Healthcare	1	4
1	2	Male	21	35000	81	Engineer	3	3
2	3	Female	20	86000	6	Engineer	1	1
3	4	Female	23	59000	77	Lawyer	0	2
4	5	Female	31	38000	40	Entertainment	2	6
```
