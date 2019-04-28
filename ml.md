---
layout: page
title: Wildfire Cause Prediction
subtitle: Python
---

<div class="main-explain-area jumbotron">
  <p>The secondary motivation of this project is uses a machine learning approach to analyze the wildfire data to predict the causes of wildfires. Core models are Random Forest, Neural Network, and Supoort Vector Machine(SVM).  </p>
</div>

# Package
  - Numpy 
  - Pandas
  - Scikit-lean
  - Matplotlib

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
# Machine Learning
1. MLPClassifier
2. Logistic Regression Model
3. Support Vector Model
    (I had to kill the gradient boost, my low spec laptop couldn't cope with this algorithm and the number of rows.) 
4. Neural Net Model
5. Random Forest Classifier
6. Decision Tree Classifier


```
x <- 5 # Here's some R code
```



```
x <- 5 # Here's some R code
```

# Conclusion 




```
x <- 5 # Here's some R code
```



```
x <- 5 # Here's some R code
```
