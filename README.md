**README**

## Project Benson
### Get the MTA data
* Put the data into pandas data frame
* Explore the data through different angles
* Clean data for New Jersey stations
* Format the data and only leave applicable columns
* Analyse and handle outliers and potential incorrect values
* Plot the data to understand the trends
* Return a list of top stations sorted descending by number of exits

| Station | Weekday | Time_interval | Num_of_Exits |  
| --- | --- | --- | --- |  
| 51 ST | Monday | 2017-06-17 08:00:00 | 3144 |

* Generate MTA score associated with each identified subway station

### Tech Companies
* Utilized web-scraping to generate list of 21 most valuable tech companies' in New York
* Utilized Google Maps API to get geo-locations of the identified tech companies
* Generated tech company score associated with each identified subway station

### Starbucks
* Associated Files: Starbucks_and_Census_Alan.ipynb
* Utilized Google Maps API to find the geo-locations of the Starbucks surrounding each identified subway station
* Generated Starbucks score associated with each identified subway station

### Census Data
* Associated Files: Starbucks_and_Census_Alan.ipynb, community_districts.geojson, totpop_singage_sex2010_cd.xlsx
* Incorporated US Census 2010 data and geospatial data for the NYC Community Districts (CDs) to assign a gender score to each CD
* Generated gender score based on which CD each identified subway station was located in

### Visualize the MTA data and data from other sources on a map
* Use geopandas
* Colour code the stations based on different criteria  

### Summarize & Present 
* Draw conclusions
* Write up recommendation(s)
* Build a presentation (6 min)
* Divide up the presentation topics between team members  

## Responsibilities

|Person / People | Area of Responsibility |  
| --- | --- |  
| Billy | MTA data |  
| Auste | MTA data |  
| Xu | MTA data |  
| Joyce | Web Scraping and Google Maps data (Tech Companies) |  
| Alan | Google Maps data (Starbucks), US 2010 Census Data (Gender) |
| Chelan | Visualization |
