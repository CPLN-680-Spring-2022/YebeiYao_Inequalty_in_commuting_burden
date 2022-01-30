# YebeiYao_LA_Inequalty
MUSA capstone in 2022 

## Question proposed
In this project,I'm gonna focus on the topic of "Housing-work commuting burden pattern and its inequalty contributory factor in megacities like Boston". 

## Background:
Commuting burden (with respect to both time and distance) directly influence on commuters’ quality of life.Especially with the phenomenon of urban sprawl,the living expence, sleep quality and working pressures people have to burden increase a lot more on megacities. Inequalities in commuting burdens exist among people of different economic status across the world, even in areas without widespread racial discrimination and segregation (Zhao, 2015; Roberto, 2008; Sara and Valerie, 2010; Ahmed et al., 2008).

According to statistics, the average round-trip car commute in the Boston area was 80 minutes, according to a 2019 report by Geotab, a connected vehicle company. And many people spent a lot longer than that en route in their cars or on public transportation. Specifically, Boston is tied with New York for second-worst city for commuting via car among the major cities analyzed, with an average of 40 minutes each way. 

Generally speaking, the problem of housing-work seperation greatly influence on the life quality to the workers living in megacities.People with long commutes tend to pay more for gas, typically get less sleep, have more fat, and are less happy than people who don't, according to the Dallas Business Journal.

So analyzing where in the city is suffering from more burden in commuting, and find of the contributing factors to it, will be helpful for city planners, policy makers to pay more attention to those districts.


## Current research summary:
Transport-related inequities generally relate to access to transport services, the time consumed by commuting, the monetary costs physical and psychological burdens of daily travel, and access to other services or facilities (Zhao and Howden-Chapman, 2010).

The traditional research routines mostly rely on conducting survey and collecting data from samples inside the population, which is not only expensive and time consuming, and lack of abundant data. With the technology of big data analysis, it is possible to explore larger scale of geographical spatial distribution.

As gentrification in city central areas and urban sprawl in suburbs gives rise to residential segregation (He, 2012; Smith, 2002), low-income households must relocate to suburbs far from their employment in or around the city centre (Lees, 2012; Cervero and Day, 2008). On the other hand, the unaffordability of automobiles makes low-income workers highly reliant on public transport. In addition, insufficient public transport services in suburban areas aggravate commuting problems faced by low-income workers (Ahmed et al., 2008; Zhao and Li, 2016).

## Data aspects:
The data I'm about to use are listed as follows:
Aspects of : Land usage, socio group, commuting time consuming and trip start-end point record, Economic (income, living expense, house price), convenience (infrastructure, facilities, entertainment, landmark) ,etc.

## Data link:
1. Land use data that identify residential and working district in the city.
  **Boston land use data**:[https://data.boston.gov/dataset/canopy-change-assessment-parcels-fy19-land-use1/resource/da515b12-fa11-440f-92bc-2ad81384ba1c]
   
3. ACS data that provides demographic info like population, socio-spatial group ( groups that are spatially closed, socially similar, and share similar level of socio-economic characteristics”)
with **population, races, median household income, disabilities, age**
**Neighborhood demographics**:[https://data.boston.gov/dataset/neighborhood-demographics]

5. subway, uber, bus trip... The start and drop off location, with the time consuming of the trip.
  **Boston ridership data**
  [https://mbta-massdot.opendata.arcgis.com/datasets/mbta-rail-ridership-by-time-period-season-route-line-and-stop/explore]
  [https://mbta-massdot.opendata.arcgis.com/datasets/mbta-monthly-ridership-by-mode-1/explore]
  
  **Boston MBTA lines**[https://mbta-massdot.opendata.arcgis.com/datasets/rapid-transit-routes/explore]
  **Boston MBTA stops**
  
6. Corresponding facilities (open street map or open data portal):
  **Restaurants**
  **openspace** [https://data.boston.gov/dataset/open-space1]
  **grocery stores**
  **market**
  **hospitals**[https://data.boston.gov/dataset/hospitals1]
 
7.House price(optional):
  **house rent price**


## Research method:
Leart from existing papers,I can conduct the research with mainly **ridership data** with attributes of start timestamp and start locations, drop-off timestamp and drop-off locations, **landuse data** containing residential and working district around city, which is helpful when identify the home and working space. The district with relatively longer commuting time and less **service and entertainment facilities** will be the districts underserved by public transit system,so those districts are the ones suffer from inequalty.

After I explore the commuting mobility pattern and find out the inequlty district, I could combine the result with other features using GWR or linear regression, trying to find out the influencing factor which determine which part of the city are the ones suffering commuting inequalty most.

## Use case：
Hypothetical user journey：
Possible policy implication:


## Expected deliverables:
1.Research report in the format of Rmarkdown.
2.Dynamic visualization: Animation or video or a dashboard to the commuting pattern result,especially the comparison of the inequalty.

