# GIS Project # 1
## Major Sewage Overflow Events and Poverty in Baltimore
### Topic 
Sewage overflow events are major sources of contamination in waterways and present risks to public health. They tend to occur when sewage lines are outdated in need of repairs. Within Baltimore, as the map demonstrates, these events tend to occur most often in areas of higher poverty.
### Data 
To plot data on sewage overflow events, I made use of the Maryland Department of the Environment, Reported Sewer Overflow Database. For data on poverty, I used percent of food stamp recipients from the 2019 ACS.
### Transformations
Using R and tinycensus, I was able to create a data set on the share of food stamp recipients by census tract within the City of Baltimore. In QGIS, I mapped these along a color gradient. I imported data from the MDE on sewage overflow events and created a shapefile from it. I then plotted data points by size of overflow event, with the largest events in gallons of sewage displayed as the largest points. I ignored the many minor overflow events (under 10,000 gallons).
### Analysis
The map shows that major sewage overflow events correlate closely to areas of poverty in Baltimore, as measured by percent of food stamp recipients. 
### Outputs
Map showing Percent of Food Stamp Recipents vs. Major Sewage Overflow Events
