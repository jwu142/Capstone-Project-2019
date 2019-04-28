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
  - Load the data 
  - Clean the Data
    - Julian Date format to Gregorian dates
      ```
      #Julian Date format to Gregorian dates
      fires['DATE'] = pd.to_datetime(fires['DISCOVERY_DATE'] - pd.Timestamp(0).to_julian_date(), unit='D')
      fires['MONTH'] = pd.DatetimeIndex(fires['DATE']).month
      fires['DAY_OF_WEEK'] = fires['DATE'].dt.weekday_name
      ```

# Machine Learning
1. MLPClassifier
2. Logistic Regression Model
3. Random Forest Classifier
4. Decision Tree Classifier
5. Support Vector Model (I had to kill the gradient boost, my low spec laptop couldn't cope with this algorithm and the number of rows.) 


```
x <- 5 # Here's some R code
```
# Pipeline Method
  - Create the dictionary of parameter grids
  - Hyperparameter tuning
  - Model Selection
  - Predictions

```
x <- 5 # Here's some R code
```

# Conclusion 

```
x <- 5 # Here's some R code
```
