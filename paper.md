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

| **Feature Variable** | **Data Type** | **Description** |
{: .table.table-responsive} | Feature Variable | Description | | Fires |Table including wildfire data for the period of 1992-2015 compiled from US federal, state, and local reporting systems. | | FOD_ID |Global unique identifier. | | FPA_ID |Unique identifier that contains information necessary to track back to the original record in the source dataset. | | SOURCE_SYSTEM_TYPE |Type of source database or system that the record was drawn from (federal, nonfederal, or interagency). | | SOURCE_SYSTEM |Name of or other identifier for source database or system that the record was drawn from. See Table 1 in Short (2014), or \Supplements\FPA_FOD_source_list.pdf, for a list of sources and their identifier. | | NWCG_REPORTING_AGENCY |Active National Wildlife Coordinating Group (NWCG) Unit Identifier for the agency preparing the fire report (BIA = Bureau of Indian Affairs, BLM = Bureau of Land Management, BOR = Bureau of Reclamation, DOD = Department of Defense, DOE = Department of Energy, FS = Forest Service, FWS = Fish and Wildlife Service, IA = Interagency Organization, NPS = National Park Service, ST/C&L = State, County, or Local Organization, and TRIBE = Tribal Organization). | | NWCG_REPORTING_UNIT_ID |Active NWCG Unit Identifier for the unit preparing the fire report. | | NWCG_REPORTING_UNIT_NAME |Active NWCG Unit Name for the unit preparing the fire report. | | SOURCE_REPORTING_UNIT |Code for the agency unit preparing the fire report, based on code/name in the source dataset. | | SOURCE_REPORTING_UNIT_NAME |Name of reporting agency unit preparing the fire report, based on code/name in the source dataset. | | LOCAL_FIRE_REPORT_ID |Number or code that uniquely identifies an incident report for a particular reporting unit and a particular calendar year. | | LOCAL_INCIDENT_ID |Number or code that uniquely identifies an incident for a particular local fire management organization within a particular calendar year. | | FIRE_CODE |Code used within the interagency wildland fire community to track and compile cost information for emergency fire suppression. | | FIRE_NAME |Name of the incident, from the fire report (primary) or ICS-209 report (secondary). | | ICS_209_INCIDENT_NUMBER |Incident (event) identifier, from the ICS-209 report. | | ICS_209_NAME |Name of the incident, from the ICS-209 report. | | MTBS_ID |Incident identifier, from the MTBS perimeter dataset. | | MTBS_FIRE_NAME |Name of the incident, from the MTBS perimeter dataset. | | COMPLEX_NAME |Name of the complex under which the fire was ultimately managed, when discernible. | | FIRE_YEAR |Calendar year in which the fire was discovered or confirmed to exist. | | DISCOVERY_DATE |Date on which the fire was discovered or confirmed to exist. | | DISCOVERY_DOY |Day of year on which the fire was discovered or confirmed to exist. | | DISCOVERY_TIME |Time of day that the fire was discovered or confirmed to exist. | | STAT_CAUSE_CODE |Code for the (statistical) cause of the fire. | | STAT_CAUSE_DESCR |Description of the (statistical) cause of the fire. | | CONT_DATE |Date on which the fire was declared contained or otherwise controlled (mm/dd/yyyy where mm=month, dd=day, and yyyy=year). | | CONT_DOY |Day of year on which the fire was declared contained or otherwise controlled. | | CONT_TIME |Time of day that the fire was declared contained or otherwise controlled (hhmm where hh=hour, mm=minutes). | | FIRE_SIZE |Estimate of acres within the final perimeter of the fire. | | FIRE_SIZE_CLASS | Code for fire size based on the number of acres within the final fire perimeter expenditures (A=greater than 0 but less than or equal to 0.25 acres, B=0.26-9.9 acres, C=10.0-99.9 acres, D=100-299 acres, E=300 to 999 acres, F=1000 to 4999 acres, and G=5000+ acres). | | LATITUDE |Latitude (NAD83) for point location of the fire (decimal degrees). | | LONGITUDE |Longitude (NAD83) for point location of the fire (decimal degrees). | | OWNER_CODE |Code for primary owner or entity responsible for managing the land at the point of origin of the fire at the time of the incident. | | OWNER_DESCR |Name of primary owner or entity responsible for managing the land at the point of origin of the fire at the time of the incident. | | STATE |Two-letter alphabetic code for the state in which the fire burned (or originated), based on the nominal designation in the fire report. | | COUNTY |County, or equivalent, in which the fire burned (or originated), based on nominal designation in the fire report. | | FIPS_CODE |Three-digit code from the Federal Information Process Standards (FIPS) publication 6-4 for representation of counties and equivalent entities. | | FIPS_NAME |County name from the FIPS publication 6-4 for representation of counties and equivalent entities. | | NWCG_UnitIDActive_20170109 |Look-up table containing all NWCG identifiers for agency units that were active (i.e., valid) as of 9 January 2017, when the list was downloaded from NIFC and used as the source of values available to populate the following fields in the Fires table: NWCG_REPORTING_AGENCY, NWCG_REPORTING_UNIT_ID, and NWCG_REPORTING_UNIT_NAME. | | UnitId |NWCG Unit ID. | | GeographicArea |Two-letter code for the geographic area in which the unit is located (NA=National, IN=International, AK=Alaska, CA=California, EA=Eastern Area, GB=Great Basin, NR=Northern Rockies, NW=Northwest, RM=Rocky Mountain, SA=Southern Area, and SW=Southwest). | | Gacc |Seven or eight-letter code for the Geographic Area Coordination Center in which the unit is located or primarily affiliated with (CAMBCIFC=Canadian Interagency Forest Fire Centre, USAKCC=Alaska Interagency Coordination Center, USCAONCC=Northern California Area Coordination Center, USCAOSCC=Southern California Coordination Center, USCORMCC=Rocky Mountain Area Coordination Center, USGASAC=Southern Area Coordination Center, USIDNIC=National Interagency Coordination Center, USMTNRC=Northern Rockies Coordination Center, USNMSWC=Southwest Area Coordination Center, USORNWC=Northwest Area Coordination Center, USUTGBC=Western Great Basin Coordination Center, USWIEACC=Eastern Area Coordination Center).| | WildlandRole |Role of the unit within the wildland fire community. | | UnitType |Type of unit (e.g., federal, state, local). | | Department |Department (or state/territory) to which the unit belongs (AK=Alaska, AL=Alabama, AR=Arkansas, AZ=Arizona, CA=California, CO=Colorado, CT=Connecticut, DE=Delaware, DHS=Department of Homeland Security, DOC= Department of Commerce, DOD=Department of Defense, DOE=Department of Energy, DOI= Department of Interior, DOL=Department of Labor, FL=Florida, GA=Georgia, IA=Iowa, IA/GC=Non-Departmental Agencies, ID=Idaho, IL=Illinois, IN=Indiana, KS=Kansas, KY=Kentucky, LA=Louisiana, MA=Massachusetts, MD=Maryland, ME=Maine, MI=Michigan, MN=Minnesota, MO=Missouri, MS=Mississippi, MT=Montana, NC=North Carolina, NE=Nebraska, NG=Non-Government, NH=New Hampshire, NJ=New Jersey, NM=New Mexico, NV=Nevada, NY=New York, OH=Ohio, OK=Oklahoma, OR=Oregon, PA=Pennsylvania, PR=Puerto Rico, RI=Rhode Island, SC=South Carolina, SD=South Dakota, ST/L=State or Local Government, TN=Tennessee, Tribe=Tribe, TX=Texas, USDA=Department of Agriculture, UT=Utah, VA=Virginia, VI=U. S. Virgin Islands, VT=Vermont, WA=Washington, WI=Wisconsin, WV=West Virginia, WY=Wyoming). | | Agency |Agency or bureau to which the unit belongs (AG=Air Guard, ANC=Alaska Native Corporation, BIA=Bureau of Indian Affairs, BLM=Bureau of Land Management, BOEM=Bureau of Ocean Energy Management, BOR=Bureau of Reclamation, BSEE=Bureau of Safety and Environmental Enforcement, C&L=County & Local, CDF=California Department of Forestry & Fire Protection, DC=Department of Corrections, DFE=Division of Forest Environment, DFF=Division of Forestry Fire & State Lands, DFL=Division of Forests and Land, DFR=Division of Forest Resources, DL=Department of Lands, DNR=Department of Natural Resources, DNRC=Department of Natural Resources and Conservation, DNRF=Department of Natural Resources Forest Service, DOA=Department of Agriculture, DOC=Department of Conservation, DOE=Department of Energy, DOF=Department of Forestry, DVF=Division of Forestry, DWF=Division of Wildland Fire, EPA=Environmental Protection Agency, FC=Forestry Commission, FEMA=Federal Emergency Management Agency, FFC=Bureau of Forest Fire Control, FFP=Forest Fire Protection, FFS=Forest Fire Service, FR=Forest Rangers, FS=Forest Service, FWS=Fish & Wildlife Service, HQ=Headquarters, JC=Job Corps, NBC=National Business Center, NG=National Guard, NNSA=National Nuclear Security Administration, NPS=National Park Service, NWS=National Weather Service, OES=Office of Emergency Services, PRI=Private, SF=State Forestry, SFS=State Forest Service, SP=State Parks, TNC=The Nature Conservancy, USA=United States Army, USACE=United States Army Corps of Engineers, USAF=United States Air Force, USGS=United States Geological Survey, USN=United States Navy). | | Parent |Agency subgroup to which the unit belongs (A concatenation of State and Unit from this report - https://www.nifc.blm.gov/unit_id/publish/UnitIdReport.rtf). | | Country |Country in which the unit is located (e.g. US = United States). | | State |Two-letter code for the state in which the unit is located (or primarily affiliated). | | Code |Unit code (follows state code to create UnitId). | | Name |Unit name. |

