# Citi Bike Sharing Analysis in NYC
## Overview
This is an analysis of Citi bike data from August 2019 from New York City to help propose a similar bike sharing program in Des Moines.
## Results
A full analysis of the bike sharing data from New York City in August 2019 is conducted using Tableau to show the top sharing locations, bike trip duration by gender and time, detailed bread down of clientale by gender, user type and age. The analysis is shown by Tableau story link as [link to story](https://public.tableau.com/views/BikeSharingAnalysisinNYCStory/BikeSharingAnalysisinNYc?:language=en-US&:display_count=n&:origin=viz_share_link)

### Figure 1. Top Bike Sharing Locations. <br/>
 ![top_locations](/Resources/story1.png) <br/>
 
 - All the bike trip locations from starting and ending point are matched on the map from New York City, each dot represents the number of bike trips from each location by colour and size. it shows that most of the bike rides are in Manhattan where population and tourism is the most concentrated. Bike trips outside of Manhattan is less frequent.
 
### Figure 2. Length of Time for Bike Sharing by Users. <br/>
![checkout_alluser](/Resources/story2.png) <br/>

- The length of time that bikes are checked out for all riders is shown by minutes and filtered by hours. Majority of the bike sharing time is within one hour. The duration of trip is mainly within 30 mins and peaks at 5 mins. Number of bike rides significantly drop after 1 hour, indicating most of the biking share is for short trips not long trips.
  
### Figure 3. Length of Time for Bike Sharing by Gender. <br/>
![checkout_gender](/Resources/story3.png) <br/>

- The length of checkout time for biking trips is compared within genders. Overall pattern for male and female is similar that both gender ride bikes for short term tirp within one hour. There are siginificantly more men than women using bike sharing service for short term within one hour. For longer trips more than 1 hours, the difference is smaller. 
   
### Figure 4. Bike Trips by Time. <br/>
![trip_time](/Resources/story4.png) <br/>

- The number of bike trips for all riders for each hour of each day of the week is shown in the heatmap. It shows that most of the bike trips are around 10am to 5pm on the weekend and rushing hours during weekdays (7am-9am, 5pm-7pm), indicating users probably rent bikes for leisure on the weekend and for work on the weekdays. Only exception is Wedneday, it seems like there is less traffic compared to other weekdays.

### Figure 5. Bike Trips by Time and Gender. <br/>
![triptime_gender](/Resources/story5.png) <br/>

- The number of bike trips for each hour of each day of the week between genders is shown in the heatmap. Overall pattern for male and female users during time of the day is similar as described for figure 4. There are significantly less women using the bike than men.
    
### Figure 6. User Breakdown by Gender, Weekday and User Type. <br/>
![user_breakdown](/Resources/story6.png) <br/>

- We show the overall breakdown of bike trips by gender and user type in the top two pie charts. Gender breakdown agrees with our previous finding that majority of the users are men. There are approximately 65% men, 25% women and 10% unknown of all the bike trips.  Among all the users, about 80% are subscribers and 20% are non-subscribers. 
- The heatmap shows the breakdown of number of trips for each day of the week between gender and user types. Majority of the bike trips are from male subscribers during weekdays (except Wednesday). Interestingly, data shows that subscribers tend to use more on the weekdays while non-subsribers use it more on the weekend. 

## Summary
- Majority of the bike rides users are male subscribers. The most bike trips are short term trips within one hour from rush hours on weekdays and day time during weekend. Most of the rides are in Manhattan. 
- User breakdown suggests that most of the subscribers use bike sharing for commuting to work and non-subscribers use it on the weekend, probably from tourists.
- Overall data suggests the prodominat target group in metropolitan cities are male workers and also potential tourists. To establish a bike sharing program in Des Moines, considering the population and density, some conditions may apply for workers but we need to modify expectations and strategy for smaller capital cities. 

### Figure 7. User Breakdown by Age. <br/>
![user_age](/Resources/story7.png) <br/>

- Additional recommaned graphs are shown in figure 7. Bike usage by age and gender is plotted suggesting people between 20-40 years old are the major users for bike sharing service. The breakdown of user type by gender indicates men are more likely to subsribe than women.
