# Citi_Bike_Analysis

This project is tasked with aggregating the data found in the Citi Bike Trip History Logs to build a data dashboard,story, or report using Tableau. The Citi Bike Trip History Logs are posted publicly on the Citi Bike <a href="https://www.citibikenyc.com/system-data">website</a>.

The data includes:

<ul>
  <li>Trip Duration (seconds)</li>
  <li>Start Time and Date</li>
  <li>Stop Time and Date</li>
  <li>Start Station Name</li>
  <li>End Station Name</li>
  <li>Station ID</li>
  <li>Station Lat/Long</li>
  <li>Bike ID</li>
  <li>User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)</li>
  <li>Gender (Zero=unknown; 1=male; 2=female)</li>
  <li>Year of Birth</li>
</ul>

This data has been processed to remove trips that are taken by staff as they service and inspect the system, trips that are taken to/from any of our “test” stations, and any trips that were below 60 seconds in length (potentially false starts or users trying to re-dock a bike to ensure it's secure).

<b>Data sets used:</b>

New York City Trips from January 2019 through May 2019

<b>Data cleaning:</b>

Removed entries with birth year < 1939 (or age > 80).
Removed entries with trips that are over 24 hours. Bikes checked out for more than 24 hours are considered lost/stolen.
Final data set contained 6,918,077 records.

<b>Dashboards:</b>

Total number of trips recorded during the time period.
Average duration of trips.
User demographics based on gender and age.
Short-term customers and annual subscribers.
Top 10 stations for starting/ending trips.
Bottom 10 stations for starting/ending trips.
Individual bike usage. 

<b>Visualizations:</b>

A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.

A dynamic map that shows how each station's popularity changes over time by month
