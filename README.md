# Citi_Bike_Analysis

This project is tasked with aggregating the data found in the Citi Bike Trip History Logs to build a data dashboard,story, or report using Tableau. The Citi Bike Trip History Logs are posted publicly on the Citi Bike<a href="https://www.citibikenyc.com/system-data">website</a>.

The data includes:

Trip Duration (seconds)
Start Time and Date
Stop Time and Date
Start Station Name
End Station Name
Station ID
Station Lat/Long
Bike ID
User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
Gender (Zero=unknown; 1=male; 2=female)
Year of Birth

This data has been processed to remove trips that are taken by staff as they service and inspect the system, trips that are taken to/from any of our “test” stations, and any trips that were below 60 seconds in length (potentially false starts or users trying to re-dock a bike to ensure it's secure).

Data sets used:

New York City Trips from January 2019 through May 2019

Data cleaning:

Removed entries with birth year < 1939 (or age > 80).
Removed entries with trips that are over 24 hours. Bikes checked out for more than 24 hours are considered lost/stolen.
Final data set contained 6,918,077 records.

Questions:

How many trips have been recorded total during the chosen period?
By what percentage has total ridership grown? 
How has the proportion of short-term customers and annual subscribers changed?
What are the peak hours in which bikes are used during summer months? 
What are the peak hours in which bikes are used during winter months?
Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)
Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)
Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)
Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)
Today, what is the gender breakdown of active participants (Male v. Female)?
How effective has gender outreach been in increasing female ridership over the timespan?
How does the average trip duration change by age?
What is the average distance in miles that a bike is ridden?
Which bikes (by ID) are most likely due for repair or inspection in the timespan? 
How variable is the utilization by bike ID?

Visualizations:

A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.

A dynamic map that shows how each station's popularity changes over time (by month and year) -- with commentary pointing to any interesting events that may be behind these phenomena.

Find at least two unexpected phenomena in the data and provide a visualization and analysis to document their presence.