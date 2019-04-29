---
layout: page
title: Wildfire Cause Prediction
subtitle: Python, AWS
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
      fires['DATE'] = pd.to_datetime(fires['DISCOVERY_DATE'] - pd.Timestamp(0).to_julian_date(), unit='D')
      fires['MONTH'] = pd.DatetimeIndex(fires['DATE']).month
      fires['DAY_OF_WEEK'] = fires['DATE'].dt.weekday_name
      ```
  - Categorize the cause to accident, human-caused and other.
    ```
    def cat3 (cats):
    if cats in ['Lightning','Structure','Powerline','Railroad']:
        return 'accident'
    elif cats in ['Arson','Smoking','Children','Campfire','Equipment Use','Debris Burning','Fireworks']:
        return 'human_caused'
    else:
        return 'other'
    # Make two dataframes 
    df3cats = df.copy() # make a copy to keep things neat
    df3cats['STAT_CAUSE_DESCR'] = df3cats['STAT_CAUSE_DESCR'].apply(cat3)
    categorizeCAUSE3Cats = df3cats.groupby('STAT_CAUSE_DESCR').STAT_CAUSE_DESCR.count()
    ```

# Machine Learning
1. MLPClassifier: 
   - Accuracy: 0.6791674983919977
   
2. Logistic Regression Model
   - Accuracy: 0.5626011932486082
   
3. Random Forest Classifier
   - Accuracy: 0.690088051988378
   
4. Decision Tree Classifier
   - Accuracy: 0.6334919156297825
   
5. Support Vector Model (I had to kill the gradient boost, my low spec laptop couldn't cope with this algorithm and the number of rows.) 

# Pipeline Method
  - Create the dictionary of parameter grids
  - Hyperparameter tuning
  - Model Selection
  - Predictions
  ### I have to give up for this process. My dataset is huge, I did a similar process before, but this time, I waited like a half day, but still didn't get any result.
  
# Conclusion 

In conclusion, the we discovered that the Random Forest model with a 70.19% accuracy, with its ability to robustly handle noise in datasets, was the best suited to our wildfires dataset. 


<div class="get-started-wrap">
  <a class="btn btn-success btn-lg get-started-btn" href="https://github.com/jwu142/Capstone-Project-2019/tree/master/">ML Code!</a>
</div>
