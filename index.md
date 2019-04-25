---
layout: page
title: 1.88 Million US Wildfires Analysis
subtitle: Data Science Capstone_DATS_6501_10
bigimg: /img/joanne-francis-978866-unsplash.jpg
---

## Here is where we can insert an image:

![GW Data Science logo](/img/gwdsp.png)

## How about a link?

And of course some text, and maybe [a link to https://datasci.columbian.gwu.edu/](https://datasci.columbian.gwu.edu/)

## Or some code?

Some code might go here:

```
x <- 5 # Here's some R code
```

What if I just paste the HTML for a plotly plot?

We can do it with a line of markdown that looks like this (without the slashes - I haven't solved that problem just yet...):
```
\{\% include jupyter-basic_bar.html \%\}
```
{% include flourish.html %}


1.88 Million US Wildfires Analysis

Jiajun Wu, M.S.

Nima Zahadat, Ph.D.

The George Washington University





**ABSTRACT**

Wildfires are often caused by lightning, and other common causes such as negligence, deliberate arson, volcanic eruptions, pyroclastic clouds, heat waves, droughts and periodic climate shifts such as El Nino which can dramatically increase the risk of wildfires. The purpose of this capstone project was to demonstrate data visualizing techniques and machine learning methods to predict the causes of wildfire and analyze wildfires in the States during a 24-year period (1992-2015). 

*Keywords:_ Data Mining; Random Forest Classifier; Logistic Regression; location; Fire; Fire detection; wildfire; Fire Program Analysis; United States; GIS; Machine Learning; Data Visualization.*

**INTRODUCTION**

The effects of wildfires are manifold. They can have a significant negative impact on the economy, environment, heritage and social fabric of rural areas. A little spark kindles a great fire. In recent years, as fire incidents in the United States have become larger and more destructive, the government and related departments urgently need to develop long-term social and ecological strategies to mitigate the impact. Climate change is a factor to increase wildfires. However, most of wildfires were caused by humans. 

This project mainly uses data visualizing to analyze the 1.88 million U.S. wildfires from 1992 to 2015 to predict the cause of a wildfire. And also, this project uses a machine learning approach to predict the cause of wildfire based on location, date (season), fire size and fire causes. Our motivation for this project is to apply the machine learning model, and also some data visualization methods to solve a real-world problem. The next few tools such as Python, JavaScript, Web, API, Tableau, Python libraries, machine learning, and visualization techniques will be used in this project. 

Modeling for machine learning part is focused on the following features: Description of the (statistical) cause of the fire, latitude, longitude, fire size, discovery date, month, week of day, and state. We tested several different methods to model our dataset, all involving our core three models: random forest, neural network, and support vector machine (SVM). This project gives comprehensive results of several methods, including oversampling, PCA, and hyperparameter tuning. 

In the end, the results are reviewed, and suggestions for further study are put forward. Random Forest Classifier can predict the causes of the wildfire with a 72.78% accuracy.


**LITERATURE REVIEW**

Wildfires (also known as forest or peat fires) are a type of fire that cannot be controlled and generally viewed as undesirable by land managers. Wildfires often occur in wild, uninhabited areas, but they can occur anywhere and harm agriculture, humans, and animals in their path. Wildfires are caused by lightning, volcanic activity, arson, or human carelessness such as campfires, cigarettes, fireworks, and machinery. According to the source from National Park Service under the U.S. Department of Interior, 90% of all wildfires are started by humans in the United States. Arson, neglect or lack of fire safety cause fires every year. And also, wildfires are often caused by lightning; 10,000 to 20,000 lightning strikes can cause fires every day. According to the record from the California Department of Forestry and Fire Protection and the National Interagency Fire Center, in 2018, a total of 8,527 fires burned an area of 1,893,913 acres in California, including the four megafires that caused 22,280 structures destroyed and 99 confirmed deaths. And Camp Fire is the deadliest and most destructive wildfire in California to date, with 86 fatalities. About 153,336 acres were burned and 18,800 structures have been destroyed. The Camp Fire is the result of human activates and climate change, according to John Bailey, a wildfire expert and professor at Oregon State University.

**RESEARCH METHODOLOGY**

**       **  **Study Area:**

**       ** The dataset consists of 1.88 million geo-referenced wildfire records with 51 attributes representing the 140 million acres burned during the 24 years (1992-2015) in the United States.

**Packages:**

We use Python to analyze forest fire data. Specific packages used are Numpy, Pandas, and Scikit-learn. We use Matplotlib for visualizations. For the methods, I used to make my predictor, I tried Neural Net, Random Forest and Support Vector Machine (SVM). A connector was created at the beginning in order to connect to the SQL database.

**Data cleaning, preprocessing, and feature selection:**

Datasets were cleaned up before the data visualization and modeling. Data preprocessing techniques were used to reduce the samples and prepare the data for machine learning algorithms by excluding null values and converted Julian Date format to Gregorian dates. Python, JavaScript, Web, API, and Tableau were used for data visualization. Machine learning was done using Random Forest Classifier, MLP Classifier, Decision Tree Classifier, and Logistic Regression to determine whether a predictable relationship exists between the wildfires and the related features such as date, location, and states. Finally, this data analysis project can give professional experts some ideas and show general information about US wildfires.

**DATA**

The data publication contains a spatial database of wildfires in the United States from 1992 to 2015. Wildfire records were obtained from the reporting systems of federal, state and local fire organizations. The following core data elements are included in the datasets: the date of discovery, the final fire size, and the location of points. Some basic error-checking has been performed and removed as much as possible. The dataset consists of 1.88 million geo-referenced wildfire records with 51 attributes representing the 140 million acres burned during the 24 years (1992-2015).

**DATA ANALYSIS**

The dataset is an SQLite database that contains the 1.88 million wildfire records with the fifty-one attributes. The column, Fires, includes wildfire data from the period of 1992-2015 compiled from US federal, state, and local reporting systems. Country, state, discovery date, geographic area, latitude, longitude, and fire size were updated and organized uniformly and accurately. 

Python was used to analyze the US wildfires data. Specific packages used are NumPy, Pandas, and Scikit-learn. For the methods used to make predictor, Neural Net, Random Forest and Supoortt Vector Machine (SVM). Tableau provided support for almost all data visualizations including bar-charts, line chart, symbol map, geo-map, packed bubbles, bullet graphs, pie chart and heat map. Folium is a powerful data visualization library for helping people visualize geospatial data in Python. Geographic heat maps are animated based on certain dimensions using a class method called HeatMapWithTime(). The code is publicly available at [www.github.com](https://github.com/jwu142/Capstone-Project-2019/tree/master). 





**KEY FINDINGS**

Debris burning is the largest cause of US wildfires. Arson is the third cause of wildfires. Most of wildfires were human-caused such as arson, equipment uses, campfire, children, smoking, railroad, powerline, fireworks, and structure. According to the statistic, the record of Human-caused wildfire is larger than the sum of Other and Accident. Human is the chief culprit of wildfire.

 Sum of fire size and the number of records compared in the past 24 years. In general, the number of wildfires is going to decrease. However, that does not mean the wildfire is going more threat less for human because the fire size is going more and more larger even though the number of records is going decrease.

        The fire size by county was created by Tableau. The biggest wildfire was located in Alaska and the fire size looks extremely large than the rest of wildfires. According to records, the biggest wildfire in the US history in the past 24 years was happened in the Alaska in 2004, and the fire size is 606,945 acres. And also, the accumulated fire size in this area is 32,232,475 acres in the past 24 years. The 2004 Alaska fire season was the worst on record in terms of area burned by wildfires in the U.S. state of Alaska. Wildfires are rarely happened in the Northeast and Midwest , and most of big wildfire located in the West, South,























**RECOMMENDATIONS**

Going forward, if we were to continue our study of the wildfire&#39;s dataset, there are some additional steps we can going deeper.

With the increase of global climate, wildfire will be more frequency in the next decades if people who do not pay attentions to manage forest. This dataset is well documented however, if there more detail needs to be added in future. The wildfire can be classified more specifically as a brush fire, desert fire, forest fire, grass fire, hill fire, peat fire, vegetation fire, or veld fire based on

The datasets can be further improved in the future. And







**CONCLUSION**





























**BIOGRAPHY**

**Jiajun Wu** is a graduate student in the Data Science Program at The George Washington University. He received his bachelor&#39;s degree from Delaware State University and majored in Agribusiness. During his previous college internships, he dealt with a variety of agriculture research, conducted market research and handled some administrative duties. He has supported some research projects about plant science and soil science. He is interning at the Peace Crops as a data analyst. He enjoys reading, hiking, and cooking in his spare time.

**Dr. Nima Zahadat**  is a professor of data science, information systems security, and digital forensics. His research focus is on studying the Internet of Things, data mining, information visualization, mobile security, security policy management, and memory forensics. He has been teaching since 2001 and has developed and taught over 100 topics. Dr. Zahadat has also been consultant with the federal government agencies, the US Air Force, Navy, Marines, and the Coast Guard. He enjoys teaching, biking, reading, and writing.

**REFERENCES**

**CITATION:**

Citation: These data were collected using funding from the U.S. Government and can be used without additional permissions or fees. If you use these data in a publication, presentation, or other research product please use the following citation:

Short, Karen C. 2017. Spatial wildfire occurrence data for the United States, 1992-2015 [FPA\_FOD\_20170508]. 4th Edition. Fort Collins, CO: Forest Service Research Data Archive. [https://doi.org/10.2737/RDS-2013-0009.4](https://doi.org/10.2737/RDS-2013-0009.4)























**APPENDIX A**

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
