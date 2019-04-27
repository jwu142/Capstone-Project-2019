---
layout: page
title: 1.88 Million US Wildfires Analysis
subtitle: Data Science Capstone_DATS_6501_10
bigimg: /img/joanne-francis-978866-unsplash.jpg
---

## How about a link?

<div class="get-started-wrap">
  <a class="btn btn-success btn-lg get-started-btn" href="https://github.com/daattali/beautiful-jekyll#readme">Get Started!</a>
</div>


And of course some text, and maybe [a link to https://datasci.columbian.gwu.edu/](https://datasci.columbian.gwu.edu/)

```
x <- 5 # Here's some R code
```

We can do it with a line of markdown that looks like this (without the slashes - I haven't solved that problem just yet...):
```
\{\% include jupyter-basic_bar.html \%\}
```
{% include flourish.html %}


<center> 1.88 Million US Wildfires Analysis </center>

Jiajun Wu, M.S.

Nima Zahadat, Ph.D.

The George Washington University

![GW Data Science logo](/img/gwdsp.png)



**ABSTRACT**

Wildfires are often caused by lightning, and other common causes such as negligence, deliberate arson, volcanic eruptions, pyroclastic clouds, heat waves, droughts and periodic climate shifts such as El Nino which can dramatically increase the risk of wildfires. The purpose of this capstone project was to demonstrate data visualizing techniques and machine learning methods to predict the causes of wildfire and analyze wildfires in the States during a 24-year period (1992-2015). 

*Keywords:_ Data Mining; Random Forest Classifier; Logistic Regression; location; Fire; Fire detection; wildfire; Fire Program Analysis; United States; GIS; Machine Learning; Data Visualization.*

**INTRODUCTION**

The effects of wildfires are manifold. They can have a significant negative impact on the economy, environment, heritage and social fabric of rural areas. A little spark kindles a great fire. In recent years, as fire incidents in the United States have become larger and more destructive, the government and related departments urgently need to develop long-term social and ecological strategies to mitigate the impact. Climate change is a factor to increase wildfires. However, most of wildfires were caused by humans. 

This project mainly uses data visualizing to analyze the 1.88 million U.S. wildfires from 1992 to 2015 to predict the cause of a wildfire. And also, this project uses a machine learning approach to predict the cause of wildfire based on location, date (season), fire size and fire causes. Our motivation for this project is to apply the machine learning model, and also some data visualization methods to solve a real-world problem. The next few tools such as Python, JavaScript, Web, API, Tableau, Python libraries, machine learning, and visualization techniques will be used in this project. 

Modeling for machine learning part is focused on the following features: Description of the (statistical) cause of the fire, latitude, longitude, fire size, discovery date, month, week of day, and state. We tested several different methods to model our dataset, all involving our core three models: random forest, neural network, and support vector machine (SVM). This project gives comprehensive results of several methods, including oversampling, PCA, and hyperparameter tuning. 

In the end, the results are reviewed, and suggestions for further study are put forward. Random Forest Classifier can predict the causes of the wildfire with a 72.78% accuracy.



| **Feature Variable** | **Data Type** | **Description** |
| --- | --- | --- |
| URL\_LENGTH | Int | The number of characters in the URL |
| NUMBER\_SPECIAL\_CHARACTERS | Int | The number of special characters identified in the URL, such as &quot;/&quot;, &quot;%&quot;, &quot;#&quot;, &quot;&amp;&quot;, &quot;. &quot;, &quot;=&quot; |
| WHOIS\_STATEPRO | Object | The states received from the server response |
| TCP\_CONVERSATION\_EXCHANGE | Int | The number of TCP packets exchanged between the server and the honeypot client |
| DIST\_REMOTE\_TCP\_PORT | Int | The number of the ports detected |
| REMOTE\_IPS | Int | The number of IPs connected to the honeypot |
| APP\_BYTES | Int | The number of bytes transferred |
| SOURCE\_APP\_PACKETS | Int | Packets sent from the honeypot to the server |
| REMOTE\_APP\_PACKETS | Int | Packets received from the server |
| APP\_PACKETS | Int | The number of IP packets generated during the communication between the honeypot and the server |
| DNS\_QUERY\_TIMES | Int | The number of DNS packets generated during the communication between the honeypot and the server |
| TYPE | Int | The type of web page analyzed(1: malicious websites, 0: benign websites) |
