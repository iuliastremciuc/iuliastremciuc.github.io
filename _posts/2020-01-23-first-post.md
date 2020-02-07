---
layout: post
title: Analyzing crime statistics in Chicago by neighborhoods
bigimg: /img/ChicagoSkyline.jpg
--- 
I have always had an interest in law enforcement, and for this data science project I thought getting and analyzing crime statistics for the city I live in would be a way to practice the skills I have learned in the first weeks of Lambda School data science program an interesting way.
I was raised in Ukraine and moved to the Chicago in Nov 2015. As a foreigner, there is so much Americans, and Chicagoans in particular, know about the city of Chicago that I had no idea about. 
Besides trips to popular places in the city during the day, I lived, worked, and shopped in a neighborhood with a fair mix of working class immigrants and American citizens. 
I never really thought about crime in my city or neighborhood.
I found a data set available from the City of Chicago for [crime data for the year 2019](https://data.cityofchicago.org/Public-Safety/Crimes-2019/w98m-zvie).
Chicago is split up into 22 Police Districts and the City of Chicago also provides a [map shapefile](https://data.cityofchicago.org/Public-Safety/Boundaries-Police-Districts-current-/fthy-xz3r) to show those districts on a map of Chicago.
Using these files I was able to map how many crimes are committed per district and display that in an easy to read district map of Chicago.


![Chicago Police District Map](https://crime_map (1).png)
  
  
As seen in the map, crime is not evenly distributed across the city, but is concentrated in certain areas. Even after living here for 4 years, I confess that I don’t know or have much experience with many of the neighborhoods in Chicago. 
This is pretty typical of Chicagoans who were born here and lived here their whole lives. 
People tend to live, shop, and spend their time in their own small neighborhood areas. 
Chicago has a history of being one of the most segregated cities in the United States.
I think the map clearly shows that the safety of residents of Chicago largely depends on which area of the city they live in.
The other interesting thing I found in the data provided, was the number of arrests made per reported type of crime. 
I created the below heatmap to show this data visually


![Heat Map](https://heat_map (1).png)
  
  
What’s interesting is that crimes against property and person seem to be frequent and heavily reported with very little arrests ever made. 
Commit property theft, criminal damage, burglary, assault, battery, or steal cars and you stand a good chance of getting away with it in the city of Chicago. 
Also interesting to me is that the number of narcotics arrests was higher than the reported narcotics crimes.
Of course, after thinking about it this makes sense since people generally don’t call the police to report someone using/selling drugs but police investigate drug dealers and find drugs on people arrested for other crimes.

