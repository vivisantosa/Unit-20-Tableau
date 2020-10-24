# NewYork Citibike Visualization Project<br>
<img src="/images/Screenshot (215).png" width="1080"><br>

NewYork CitiBike changed the way NewYorkers get around. We created a story to show how it has grew since its inception in interactive way.<br>

## Unit-20-Tableau
Author: Vivianti Santosa <br>
Date: 2020-10-15 <br><br>

#### https://public.tableau.com/profile/vivianti.santosa#!/vizhome/CitiBike-Vivi/Dashboard1<br><br>

This assignment is to create an interactive dashboard to tell the story of New York citibike using Tableau Public. <br>

### Data Manipulation <br>
As I use data across the years, the first data manipulation that is needed is to adjust the 2015 and 2016 data set. I use jupyter notebook-pandas to achieve that. To make chart cheration more smooth I also changed the data type for the gender and gave them aliases. <br>

From reading the file, I understand that the trip duration within the contract is 30 min for customers and 45 for subscribers. Beyond that they will be charged additional fees. Because of this, rides beyond a few hours should be an exception. Bike that does not get returned beyond 24 hour is considered lost and is heavily fined. I performed analysis on different ride duration lengths - despite believing that most of trip duration above 6 hrs is a lost bike, determining which one beyond a certain hour before 24 is considered lost is difficult, thus decided only to filter rides that are beyond 24 hrs. <br>

<img align="right" src="/images/Screenshot (220).png" width="40%">
As I worked on the file, I noticed some oddity in the data set, where a certain age group has above normal number of rides. After doing various filtering, I figured out that the above normal number actually contributes to a very specific group - born in 1969, gender 0 (not available), and have an extraordinary high trip duration. I filter this subset from my data, along with riders that was born before 1920 (which most probably a wrongly entered data). <br>
<br>

### Visualization 

The first story that I chose to explore is the year by year growth of citibike. Because of the size of the data, I chose to only use the data from each June report of the data.<br>

The second one is the exploration characteristics and information of a particular bike station. A person can choose and click a station from a list or in the map and the information will be adjusted to the particular station.<br>
<img src="/images/Screenshot (216).png" width="30%">   <img src="/images/Screenshot (217).png" width="30%">   <img src="/images/Screenshot (218).png" width="30%"><br>


## NOTES 
I originally built the visualization in tableau desktop student edition, unknowingly that it is not possible to post to tableau public from it.  I have to recreate my visualization and decided not to remake the whole 8 dashboards that I did in tableau dashboard. I take screenshots of the pages that I didn’t recreate and attached them at the end of my tableau public as pictures<br>
<img src="/images/Screenshot (212).png" width="30%">   <img src="/images/Screenshot (205).png" width="30%"><br>
