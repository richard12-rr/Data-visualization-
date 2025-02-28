## Data-visualization-

### Data-Visualization-in-excel

#### Electric Vehicle Charging Station Performance Using Excel
#### OBJECTIVES TO GUIDE THE ANALYSIS
The objective is to build a tracker for monitoring usage rates, power output, GHG saving, gasoline saving at electric vehicle charging stations. Use Excel to visualize trends in usage, peak times, and energy consumption across different locations to measure performance in United state Electric charging stations.
Data Collection 
The dataset was gotten from Kaggle and, it contains the following information:
###### •	Station Name: Name of the different station within charging entity
###### •	Org Name: The name of business Organization that owns the charging business 
###### •	Start Date: The Date charging commences, 
###### •	End Date: The date the charging ends
###### •	Start Time Zone: Start time Zone refers to start time in relation to global time zone
###### •	End Time Zone: End Time in relation to global time
###### •	Transaction Date (Pacific Time): Transaction time in relation to Pacific time zone
###### •	Total Duration: The length charging in relation to time.
###### •	Energy (kWh): Energy Consumption in terms kilowatts 
###### •	GHG Savings (kg): Green house gas savings in Kilograms
###### •	Gasoline Savings: (gallons): Gasoline saving in gallon 
######•	Port Type: the type of connector in use
###### •	Plug Type: The physical connector that plug into electric vehicle
This analysis is divided into the following stages: Data cleaning, Data Exploration & Analysis, Insights, Recommendations, and Visualization.
Data Processing & Cleaning

4 duplicate values were removed and 259411 unique values remain
![uplicated cells](https://github.com/richard12-rr/Data-visualization-/blob/main/assets%20/images/Duplicated%20data.png)
There were 5 columns that are outrightly empty with some cell but fortunately, The column and cells used for the analysis were not affected, hence to action was taken on 
![Duplicate cells](https://github.com/richard12-rr/Data-visualization-/blob/main/assets%20/images/Empty%20cells.png)
Station name were changed from lengthy text to Bryant, High, Hamiton, Webster, Cambridge, MPL, Rinconda, TED and Sherman
Analysis
### Pivot table and column chart were used for the analysis
The following questions were raised to guide in the objective achievement:
###### 1.	What is the charging rate in each of the charging stations?
###### 2.	What is the Energy output for each of the charging stations?
###### 3.	What is the trend and peak charging time in the stations?
###### 4.	What is the charging duration count?
###### 5.	What is the gasoline saving across the stations?
###### 6.	What is the charging port type Usage?
###### 7.	How is the charging plug type put into use?

###1.	Charging rate in stations
![Stationd Charging rate](https://github.com/richard12-rr/Data-visualization-/blob/main/assets%20/images/Station%20Charging%20rate.png)
From table 1.0 and fig. 1.0; it is evident that BRYANT has  the highest charging rate of 45460 count of users ID, followed by HIGH with count of Users Id 38921, HAMILTON charging station has a count of user ID 37167 in third place, WEBSTER, CAMBRIDGE, MPL, RINCONADA, TED and SHERMAN have; 36354, 31636, 27752, 17910, 16508, 32  in order of users ID count.

### 2.	The energy output in the stations
![Energy Output](https://github.com/richard12-rr/Data-visualization-/blob/main/assets%20/images/station%20energy%20output.png)
              
Figure 1.1 and table1.1 show that BRYANT sum of energy in kilowatts; 387293.5752 top the list of energy usage followed by HIGH with, HAMILTON, WEBSTER, CAMBRIDGE, MPL, RINCONADA, and TED in descending order. SHERMAN at the bottom of the table has least usage.

### 3.	The trend of charging in the charging stations
![Charging trend](https://github.com/richard12-rr/Data-visualization-/blob/main/assets%20/images/Station%20charging%20trend.png)

The rushing hour or car charging begins at 12am, it reaches the peak in the hours of 1am and decline at 2am and a charge decline in the hours of 3am to 6am. At 7, 8 and 9 all in am, charging drops to Zero according to dashboard in table 1.2 and column chart in fig 1.2

### 4.	The charging duration count? 
![Charging Duration](https://github.com/richard12-rr/Data-visualization-/blob/main/assets%20/images/Station%20Charging%20duration.png)



### 5.	The gasoline saving
![Gasoline Saving](https://github.com/richard12-rr/Data-visualization-/blob/main/assets%20/images/Station%20gasoline%20saving.png)

Dashboard, chart labelled table 1.4 and figure 1.4 indicate that BRYANT Station has the leading gasoline saving per gallon closely followed by WEBSTER
### 6.	Port type usage
![port type Usage](https://github.com/richard12-rr/Data-visualization-/blob/main/assets%20/images/Station%20port%20type%20usage.png)
Plug type J1772 is the most used plug across the charging judging by the count of charging duration in relation to plug type, this is evident in table 1.5 and figure 1.5

### 7.	Plug type Usage	
![Plug type Usage](https://github.com/richard12-rr/Data-visualization-/blob/main/assets%20/images/Station%20plug%20type%20Usage.png)
According to dashboard in tagged table 1.7 and figure 1.7, level port type is the most efficiently used.

### The Insight
###### 1.	Charging activities takes place in the night between hours 12am and 5am
###### 2.	Some charging facilities are doing better than the other, Sherman Facility is performing ridiculously poor compared with other charging stations
###### 3.	Level 2 charging port and J1772 plug are the most used are the most.

## Recommendations
###### 1.	Charging stations such as Sherman, Ted and Rinconada and canbridge where the capacity of charging facility was underutilized should look into reasons for the low patronage and get them fixed
###### 2.	Going by the recommendation number one; the following areas should be looked into to ascertain the reason for low patronages 
###### i.	The awareness of the people living in their host community about the hedge of Electric vehicle over gasoline dependent ones, if this accounted for the low patronage; aggressive advertisements and promotion must be embarked to get people switch over electric vehicles
###### ii.	Training and retraining exercise should be given to employees to have welcoming disposition to customers who comes to charge in the stations
###### iii.	 Loyalty and promotional discount should be given to car charging customers to make them come back again
###### 3.	Human resource i.e. employees must be tutored to have enough rest during day to attend to health wellbeing.
###### 4.	Burn out tendencies among employees must be addressed by giving off work days after a scheduled period of work to achieve employee retention.
###### 5.	The burden of charging all through the night hours can be shared to the day hours by operating discounted charging price from 6am till evening.    









