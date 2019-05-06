---
layout: page
title: Data Visualization 
subtitle: 1.88 Million US Wildfires
---

<div class="main-explain-area jumbotron">
  <p>This capstone project is primally focused on data visualization based on Python, Tableau, and Flourish. The motivation for this project is to apply the data visualization skills we have learned in class onto a real-world data set. </p>
</div>

[Flourish:](https://flourish.studio)  Quickly turn your spreadsheets into stunning online charts, maps and interactive stories. Animated storytelling.

[Tableau.public:](https://public.tableau.com/profile/jiajun.wu#!/) Tableau can help anyone see and understand their data. Connect to almost any database, drag and drop to create visualizations, and share with a click.

# Wildfire Causes 

{% include wildfires_record_by_cause.html %}

{% include wildfires_record_by_unclassified_cause.html %}

Humans are the chief culprits of wildfires. According to the source from National Park Service under the U.S. Department of Interior, 90% of all wildfires are started by humans in the United States.

# Wildfire Size

{% include Record_Size_by_Year_with_Trend_Line.html %}

The sum of fire sizes and the number of records is compared through the past 24 years. The year 2006 has the most wildfires. In general, the number of wildfires is going to decrease. However, that does not mean that wildfires are going to be less of a threat for humans. This is because the fire size is becoming larger even though the number of occurencies is going to decrease. 

{% include size_flourish_pie_chart.html %}

Most of wildfire sizes are between 0 to 9.9 acres; that means most of these fires can be put out on time and significant losses can be avoided through timely discovery and practical measures. However, in the past few years, the number of mega wildfires has increased extremely quickly and appears pretty hard to control. According to the previous dataset, every six years the number of large fires will reach a peak,  the next two peak times of Mega wildfires will be in 2018 and 2024.

# Geography
{% include top10flourish.html %}


{% include tableau_geo.html %}





