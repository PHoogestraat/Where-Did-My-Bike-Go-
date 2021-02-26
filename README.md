
# <div align = "center">Where Did My Bike Go? </div>
![stolen_bike_art.png](IMAGES/stolen_bike_art.png)

# Can Bike theft be predicted?

Between 2018 and 2008,  almost 5 thousand bikes were stolen in Indianapolis according to public records (fig A). Additional data can be extracted to identify where and when bikes are taken in Marion county. After compling data from the 2018 to 2008 time period the following trends can be observed:

- The months May through September have a significantly higher rate of theft then colder months. 
- Bike theft reported is highest between 12:00 A.M. and 12 P.M 
- Consistent peak around 7:00 P.M.
- These trends are consisitent regardless of month or year. 

Can this information coupled with weather data may enable the ability to identify areas of  Indianapolis that have a higher risk for theft.


![Year_month.png](IMAGES/Year_month.png)

## Bike theft during the 24 hour period (Data range 2018-2008).

![bike_time_day.png](IMAGES/bike_time_day.png)

Contrasting bike and car theft over the same period demonstrates a possible seasnal pattern that may be useful for modeling data. 


![comparison.png](IMAGES/comparison.png)


### Process (in progress): 
- [ ] Concept design and project planning.
- [ ] Create Github Repository.
- [ ] Evaluate and obtain data sources.
- [ ] Create databases to archive data.
  - [ ] Create SQL database
  - [ ] Create SQL lite database
  
- [ ] Develop a Python Flask application to create API's enabling users to explore data. 
- [ ] Generate a website with instructions for users to access API's and website content.
- [ ] Design additional web pages containing analysis, charts, interactive experiences, and data allowing users to investigate correlations between team salaries and outcomes.






### Resources (in progress):
-	HTML/CSS
-	JavaScript
-	JavaScript library
	-	[ECMAScript Internationalization API](https://402.ecma-international.org/1.0/) 		
-	Python
-	SQL
-	SQL lite

### Data Sources:
1. [IMPD_UCR_data](https://data.indy.gov/search?q=ucr&tags=ucr)
      
  OpenIndy host the data from Uniform Crime Report (UCR) program administered by the federal government in which crime statistics from across the country are reported to the FBI in a uniform manner based on crime definitions determined by the FBI. UCR Part 1 crime groups are murder, rape, robbery, aggravated assault, burglary, larceny, and vehicle theft.
        		
	
![UCR.png](IMAGES/UCR.png)
	
	
	
   2. [Kaggle: City weather](https://www.kaggle.com/selfishgene/historical-hourly-weather-data)
      
  Kaggle Data dataset containing ~5 years of high temporal resolution (hourly measurements) data of various weather attributes, such as temperature, humidity, air pressure, etc. This data is available for 30 US and Canadian Cities, as well as 6 Israeli cities.
  
![kaggle.png](IMAGES/kaggle.png)

### Data Modeling:
