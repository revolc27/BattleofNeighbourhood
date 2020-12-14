# London School Zones vs. Price Visualization
 This is my github repository of my Coursera final project (BattleofNeighbourhood)
 
 For details about the project, approach and data, please see the jupyter notebook file. The map visualization can also be accessed via the .html file.
 
### Introduction
This project tries to identify school zone neighborhoods in the Greater London area of UK and to explore the possible correlations with home price. For new immigrants, one top concern when picking the landing neighbourhood is about having good access to schoolings. 

For simplicity, the initial project focuses on only the Greater London area.  But this is a scalable project that can expand to other geographies and also take consideration of other metrics such as crime rate, transportation, average income, etc into consideration.

### Data
To perform the analysis, we collected data from 4 major sources:
- UK's postcode and geocode data (longitude & latitude) from FreeMapTools ([Link](https://www.freemaptools.com/download-uk-postcode-lat-lng.htm))
- UK home price data from Gov.uk ([link](https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads))
- Greater London area's postal districts and neighbourhoods from Wikipedia
- Venue data from Foursquare API

### Premilinary Conclusions
1. For migrant families with kids that require school placement, Cluster 0 areas generally would have less choices  
2. For families with young kids whom go to nursery or elementary schools, Cluster 1 areas would have more choices 
3. One may consider Cluster 1 areas in the outter rings of Greater London with relatively lower home prices
