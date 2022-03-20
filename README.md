# Bike-Sharing Program 

## Overview

### Purpose

The purpose of this analysis is to provide investors a comprehensive bike trip analysis to demonstrate a bike-sharing program in Des Moines, Iowa is a solid business proposal. The bike-sharing program is presented as an eco-friendly all-year round service to locals and tourists in the greater Des Moines, which is the fastest-growing metro in the Midwest. 

For this analysis, Python and Pandas functions were used to change the "tripduration" column from an integer to a datetime datatype. Additionally, by performing an exploratory analysis on the NYC Citi Bike trip data for the month of August, a set of high-quality visualizations was created using Tableau. Now, investors have all the data they need to make an educated decision on the two-wheel venture. Let’s go!

<p float="left">
  <img src="Images/hightrestletrail.jpg " width="400" height="280" />
  <img src="Images/nycbike.png " width="600" height="280" />
</p>


## Results

### Dataset, Files and Links

The analysis is based on the following:

* Code - Datetime Data Type Conversion: [NYC_CitiBike_Challenge](NYC_CitiBike_Challenge.ipynb)
* Tableau Public link - Bike Sharing Story: [link to dashboard](LINK GOES HERE)
[link to dashboard](LINK GOES HERE "link to dashboard")

### Software and Application

The software and web-based application used for this analysis are:

* Python Version 3.7.11 (using PythonData environment and Pandas Library)
* Jupyter Notebook Version 6.4.6
* Tableau Public Version 2021.4.4

### Outcomes 

* Mention total number or rides for August xxx: 1,900,359 or xx% subscribers and 443,865 or xx% customers.
* Gender portions: male, female and unknown.

Furthermore, a set of visualizations were created to display valuable data/key findings/outcomes of bike trips in New York City during the month of August. A description of the results for each visualization is included as well. 

**Checkout Times for Users**

![1checkout_times_users](Images/1checkout_times_users.png)

In this visualization, a line graph displays the number of bikes checked out by duration for all users, that is by customers or subscribers. Along the x-axis are the minutes of a trip duration, and the y-axis is the number of bikes. The line graph can be filtered by the hour for further comparison. For example, there were 146,752 bikes that were checked out between 12 AM and 1 AM with a trip duration of 5 minutes as shown in the graph. 


**Checkout Times by Gender**

![2checkout_time_gender](Images/2checkout_time_gender.png)

In this visualization, a line graph displays the number of bikes checked out by duration for each gender; that is male, female or unknown. Along the x-axis are the minutes of a trip duration, and the y-axis is the number of bikes. The line graph can be filtered by gender and the hour for further comparison. Also, the line graph is color coded orange for male, blue for female and red for unknown. For example, the orange line states that 108,087 male users checked out a bike between 12 AM and 1 AM with a trip duration of 5 minutes as shown in the graph.


**Trips by Weekday for Each Hour**

![3trips_weekday_hour](Images/3trips_weekday_hour.png)

In this visualization, a heatmap is created showing the number of bike trips for each hour of each day of the week. Along the x-axis is the stop time filtered by weekday, and the y-axis is the start time filtered by the hour. The darker the block the higher the number of trips. For example, the highest number of bike trips are on Thursdays recorded at 44,905 between 6 PM and 7 PM. 


**Trips by Gender (Weekday per Hour)**

![4trips_gender_hour](Images/4trips_gender_hour.png)

In this visualization, a heatmap is created showing the number of bike trips by gender for each hour of each day of the week. Along the x-axis is the gender and the stop time filtered by weekday, and the y-axis is the start time filtered by the hour. The heatmap can be filtered by gender as well. As noted earlier, the genders are identified as male, female and unknown. For example, the highest number of bike trips are on Thursdays recorded at 30,749 by male users between 6 PM and 7 PM.   


**User Trips by Gender by Weekday**

![5usertrip_gender](Images/5usertrip_gender.png)

In this visualization, a heatmap is created showing the number of bike trips for each type of user and gender for each day of the week. Along the x-axis is the gender, and the y-axis is the user type and the start time filtered by the weekday. The heatmap can be filtered by user type and gender as well. As noted earlier, the user type is identified as customer or subscriber. The darker the block the higher the number of trips. For example, the highest number of bike trips are on Thursdays recorded at 259,316 by subscribers identified as male. 


**August Peak Hours**

![6august_peakhours](Images/6august_peakhours.png)

In this visualization, a horizontal bar graph is created showing peak riding hours by user type during the month of August. Along the x-axis is the number of trips, and the y-axis is the start time filtered by the hour. The bar graph can be filtered by user type and hour as well. As noted earlier, the user type is identified as customer or subscriber. Also, the bar graph is color coded orange for subscriber and blue for customer. For example, the first orange bar states that 185,673 subscribers checked out a bike between 17 hours or 5 PM and 18 hours or 6 PM, which is the highest peak riding hour as shown in the graph.


**Top Starting Locations**

![7top_startingloc](Images/7top_startingloc.png)

In this visualization, a symbol map is created showing the most popular stations in New York City for starting a bike journey by user type during the month of August. The symbol map can be filtered by user type as well. As noted earlier, the user type is identified as customer or subscriber. The symbol map is color coded to identify the top starting locations; dots closer to the red color are more popular locations and dots closer to the blue color are less popular locations. For example, the dark red dot as shown on the symbol map is Pershing Square North where Grand Central Station is located, and it is the most popular location to start a bike ride with a record of 16,564 users.

      
## Summary - TO COMPLETE!!!

There is a high-level summary of the results:

One trend we can observe based on this analysis is male users whether subscriber or customer are the key gender for the bike-sharing program. In addition, the date shows that it is also commuters that travel to and from the city use the citi bikes the most. Work in Manhattan. Start and end in the most transited train and subway stations.  

Below are two additional visualizations suggested for future analysis.

1.**Top 10 Starting Stations**

![8top_startstation](Images/8top_startstation.png)

In this visualization, a horizontal bar graph is created showing the top 10 starting stations by user type during the month of August. Along the x-axis is the number of trips, and the y-axis is the start station name. The bar graph can be filtered by user type as well. As noted earlier, the user type is identified as customer or subscriber. Also, the bar graph is color coded orange for subscriber and blue for customer. For example, the first orange bar states that 14,571 subscribers checked out a bike at Pershing Square North where Grand Central Station is located making it the number one starting station in all New York City as shown in the graph.


2.**Top 10 Ending Stations**

![9end_topstation](Images/9end_topstation.png)

In this visualization, a horizontal bar graph is created showing the top 10 ending stations by user type during the month of August. Along the x-axis is the number of trips, and the y-axis is the end station name. The bar graph can be filtered by user type as well. As noted earlier, the user type is identified as customer or subscriber. Also, the bar graph is color coded orange for subscriber and blue for customer. For example, the first orange bar states that 14,572 subscribers checked in a bike at Pershing Square North where Grand Central Station is located making it the number one ending station in all New York City as shown in the graph.


In conclusion, an exploratory analysis on NYC Citi Bike trip data was completed to create a series of visualizations using Tableau. Additionally, Python and Pandas functions were used to change the "tripduration" column from an integer to a datetime datatype. Overall, this analysis provides investors a comprehensive bike trip analysis to demonstrate a bike-sharing program in Des Moines, Iowa can be a solid venture.
