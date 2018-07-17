# CSCI-5408-Assignment-5
1) Create a free account on Microsoft Azure Portal (Data Lake Analytics)<br/>
https://azure.microsoft.com/en-ca/services/data-lake-analytics/
2) Download a visual analytical tool of your choice (for example Power BI or<br/>
Tableau) and install it on your local system.
3) Download Traffic Signal Vehicle and Pedestrian Volumes Data dataset (CSV)<br/>
from following location: https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-catalogue/#7c8e7c62-7630-8b0f-43ed-a2dfe24aadc9<br/>
4) Load the provided data into MS Azure Data Lake using framework of your choice.<br/>
You can use any given SDK (.Net, Java, Node.js or Python).<br/>
perform following queries on the given data. For all below queries<br/>
export the output in CSV format and plot the data using visual analytical tool of<br/>
your choice.<br/>
a) Aggregate results based on “Main Street Name” and calculate average<br/>
volume of vehicles for all available years provided in the dataset. You<br/>
need to calculate one average value for each individual “Main Street<br/>
Name”.<br/>
b) Based on past 5 years of data, identify which 10 traffic locations are<br/>
busiest during peak hours (consider both vehicle traffic and pedestrian<br/>
traffic).<br/>
c) Aggregate results based on individual year (2017, 2016, 2015, etc.) and<br/>
calculate sum of vehicles and pedestrians traffic count for all available<br/>
2<br/>
locations. You need to do sum on all available locations and group them<br/>
based on individual years.<br/>
d) Considering all historic years of data and all available locations, identify<br/>
which day of the week (out of 7 days in a week) has been the busiest with<br/>
vehicle and pedestrian traffic. Export sum of final counts for all 7 days of<br/>
week for plotting.<br/>
e) Aggregate results based on “Main Street Name”, identify which day of<br/>
the week (out of 7 days in a week) has been the busiest with vehicle and<br/>
pedestrian traffic for each individual location. Include all historic data in<br/>
observation. [HINT: Group By Main Street Name, Day of Week and<br/>
calculate SUM(Vehicle Traffic + Pedestrian Traffic)]<br/>
