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

Jersey City Trips from January 2019 through May 2019 (This dataset is much smaller and was initially used to assemble the worksheets and dashboards.)

New York City Trips from January 2019 through May 2019 (This dataset is much larger.)

<b>Data cleaning:</b>

<ul>
<li>Removed entries with birth year < 1939 (or age > 80).</li>
<li>Removed entries with trips that are over 24 hours. Bikes checked out for more than 24 hours are considered lost/stolen.
</ul>

Resulting Jersey City data set contained 130,966 records.

Resulting NYC data set contained 6,918,077 records.

<b>Dashboards:</b>

<ul>
<li>Total number of trips recorded during the time period.</li>
<li>Average duration of trips.</li>
<li>User demographics based on gender and age.</li>
<li>Short-term customers and annual subscribers.</li>
<li>Top 10 stations for starting/ending trips.</li>
<li>Bottom 10 stations for starting/ending trips.</li>
<li>Individual bike usage. </li>
<li>
</ul>

<b>Visualizations:</b>

<ul>
<li>A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.</li>
<li>A dynamic map that shows how each station's popularity changes over time by month</li>
</ul>

<b>Deliverables:</b>

Jersey City Bike Usage
https://public.tableau.com/profile/cindy7982#!/vizhome/CitiBikeAnalytics-JerseyCity/CitiBikes2019

New York City Bike Usage