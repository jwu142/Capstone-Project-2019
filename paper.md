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


**LITERATURE REVIEW**

Wildfires (also known as forest or peat fires) are a type of fire that cannot be controlled and generally viewed as undesirable by land managers. Wildfires often occur in wild, uninhabited areas, but they can occur anywhere and harm agriculture, humans, and animals in their path. Wildfires are caused by lightning, volcanic activity, arson, or human carelessness such as campfires, cigarettes, fireworks, and machinery. According to the source from National Park Service under the U.S. Department of Interior, 90% of all wildfires are started by humans in the United States. Arson, neglect or lack of fire safety cause fires every year. And also, wildfires are often caused by lightning; 10,000 to 20,000 lightning strikes can cause fires every day. According to the record from the California Department of Forestry and Fire Protection and the National Interagency Fire Center, in 2018, a total of 8,527 fires burned an area of 1,893,913 acres in California, including the four megafires that caused 22,280 structures destroyed and 99 confirmed deaths. And Camp Fire is the deadliest and most destructive wildfire in California to date, with 86 fatalities. About 153,336 acres were burned and 18,800 structures have been destroyed. The Camp Fire is the result of human activates and climate change, according to John Bailey, a wildfire expert and professor at Oregon State University.

**RESEARCH METHODOLOGY**

**Study Area:**
The dataset consists of 1.88 million geo-referenced wildfire records with 51 attributes representing the 140 million acres burned during the 24 years (1992-2015) in the United States.

**Packages:**
We use Python to analyze forest fire data. Specific packages used are Numpy, Pandas, and Scikit-learn. We use Matplotlib for visualizations. For the methods, I used to make my predictor, I tried Neural Net, Random Forest and Support Vector Machine (SVM). A connector was created at the beginning in order to connect to the SQL database. 

**Data cleaning, preprocessing, and feature selection:**
Datasets were cleaned up before the data visualization and modeling. Data preprocessing techniques were used to reduce the samples and prepare the data for machine learning algorithms by excluding null values and converted Julian Date format to Gregorian dates. Python, JavaScript, Web, API, and Tableau were used for data visualization. Machine learning was done using Random Forest Classifier, MLP Classifier, Decision Tree Classifier, and Logistic Regression to determine whether a predictable relationship exists between the wildfires and the related features such as date, location, and states. Finally, this data analysis project can give professional experts some ideas and show general information about US wildfires.

**DATA**

The data publication contains a spatial database of wildfires in the United States from 1992 to 2015. Wildfire records were obtained from the reporting systems of federal, state and local fire organizations. The following core data elements are included in the datasets: the date of discovery, the final fire size, and the location of points. Some basic error-checking has been performed and removed as much as possible. The dataset consists of 1.88 million geo-referenced wildfire records with 51 attributes representing the 140 million acres burned during the 24 years (1992-2015).

**DATA ANALYSIS**

The dataset is an SQLite database that contains the 1.88 million wildfire records with the fifty-one attributes. The column, Fires, includes wildfire data from the period of 1992-2015 compiled from US federal, state, and local reporting systems. Country, state, discovery date, geographic area, latitude, longitude, and fire size were updated and organized uniformly and accurately. 

Python was used to analyze the US wildfires data. Specific packages used are NumPy, Pandas, and Scikit-learn. For the methods used to make predictor, Neural Net, Random Forest and Supoortt Vector Machine (SVM). Tableau provided support for almost all data visualizations including bar-charts, line chart, symbol map, geo-map, packed bubbles, bullet graphs, pie chart and heat map. Folium is a powerful data visualization library for helping people visualize geospatial data in Python. Geographic heat maps are animated based on certain dimensions using a class method called HeatMapWithTime(). The code is publicly available at [*github*](https://github.com/jwu142/Capstone-Project-2019/tree/master). 

**KEY FINDINGS**

Wildfires do not come from the wild. According to the U.S. National Park Service, ninety percent of wildfires are human-caused.

Debris burning is the most significant cause of US wildfires. Arson is the third cause of wildfires. Most of the wildfires were human-caused, including sources such as arson, smoking, children, campfires, equipment use, debris burning, and fireworks. According to the statistic, the record for human-caused wildfires is larger than the sum of “Other” and “Accident” (lightning, structure, powerline, and railroad). Humans are the chief culprits of wildfires.

The sum of fire sizes and the number of records is compared through the past 24 years. The year 2006 has the most wildfires. In general, the number of wildfires is going to decrease. However, that does not mean that wildfires are going to be less of a threat for humans. This is because the fire size is becoming larger even though the number of occurencies is going to decrease. 

Tableau was used to create the fire size map by each county. The biggest wildfire was located in Alaska, and the fire size looks bigger than the rest of the wildfires. According to records, the biggest wildfire in US history in the past 24 years happened in Alaska in 2004, and the fire size was 606,945 acres. Also, the accumulated fire size in this area is 32,232,475 acres in the past 24 years. The 2004 Alaska fire season was the worst on record in terms of area burned by wildfires in the U.S. state of Alaska. Wildfires rarely happen in the Northeast and Midwest, and most of the massive wildfires are located in the West and South.  

The top ten states with the highest accumulated records of wildfires from 1993 to 2019 are shown in the left dynamic chart. The records of wildfires in Georgia is increasing dramatically quick. In 1992, the Georgia record for wildfires was at 81; however, in 2006, the accumulated record of wildfires was 46,127; this ranked Georgia in the top 5 states with the highest wildfire records in the United States. The funny thing is Georgia has the highest human-caused wildfire rate with 122,766 records. That means that 11.71% of human-caused wildfires happen in Georgia. In other words, 86.76% of wildfires in Georgia are human-caused. Florida has the highest record of wildfires caused by accidents such as lightning, structure, powerline and railroad, 3.15% of the total number of wildfire records. And also, New York has the highest record of unknown caused wildfires. North Carolina has the highest accumulated wildfires record; however, North Carolina was not ranked in the top 10 states with the highest accrued wildfire size. Most wildfires in North Carolina are small-size and under control. 37.94% of wildfires are "A" size (0-0.25 acres), and 53.93% of wildfires are "B" size (0.25-0.99 acres). Idaho is the state with the highest accumulated fire size, and Texas is the state with the second highest accumulated fire size.

Most of wildfire sizes are between 0 to 9.9 acres; that means most of these fires can be put out on time and significant losses can be avoided through timely discovery and practical measures. However, in the past few years, the number of mega wildfires has increased extremely quickly and appears pretty hard to control. According to the previous dataset, every six years the number of large fires will reach a peak,  the next two peak times of Mega wildfires will be in 2018 and 2024. 

Lightning causes the largest and biggest wildfires based on the different type of wildfire size. That means lightning caused wildfires are hard to control and put out. And also, the situation becomes more complex because Miscellaneous is the second leading cause of wildfires. It will be a huge challenge for people to predict, prevent, and control wildfires.

Every year since January, the number of wildfires will be going to increase until March; then the records will drop down until May. The number of records will decrease after August. In general, the wildfire season in the States is between Feb to April and June to August. 

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


