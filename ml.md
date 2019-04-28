---
layout: page
title: Wildfire Cause Prediction
subtitle: Python
---

<div class="main-explain-area jumbotron">
  <p>The secondary motivation of this project is uses a machine learning approach to analyze the wildfire data to predict the causes of wildfires. Core models are Random Forest, Neural Network, and Supoort Vector Machine(SVM).  </p>
</div>

```
import sqlite3
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd

from sklearn.model_selection import train_test_split
from sklearn.neighbors import KNeighborsClassifier
from sklearn import preprocessing
# from sklearn.ensemble import RandomForestClassifier
import seaborn as sns
import warnings
warnings.filterwarnings("ignore")
```


# Data Preprocess

```
#Load the data 
sqlite_file = "FPA_FOD_20170508.sqlite"
conn=sqlite3.connect(sqlite_file)
c = conn.cursor()
fires = pd.read_sql_query("SELECT * FROM fires", conn)
```

```
#Julian Date format to Gregorian dates
fires['DATE'] = pd.to_datetime(fires['DISCOVERY_DATE'] - pd.Timestamp(0).to_julian_date(), unit='D')
fires['MONTH'] = pd.DatetimeIndex(fires['DATE']).month
fires['DAY_OF_WEEK'] = fires['DATE'].dt.weekday_name
```


```
x <- 5 # Here's some R code
```



```
x <- 5 # Here's some R code
```



```
x <- 5 # Here's some R code
```




```
x <- 5 # Here's some R code
```



```
x <- 5 # Here's some R code
```
