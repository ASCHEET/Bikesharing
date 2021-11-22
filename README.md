# Bikesharing
Investors are interested in replicating the CitiBiki Bike Rental model that is popular in NYC in Des Moines, IA.  Data was analyzed by ride location, gender, subscriber, and time to determine how the model could be used to determine when maintenance could be performed and where large hubs of bike rentals seemed to correlate.
Data visualization software called Tableau was used to present a business proposal for a bike-sharing company. It is used to import, style, and portray data accurately. Then, create worksheets, dashboards, and stories to visualize key data from a New York Citi Bike dataset.
Tableau is an excellent tool for data visualization. It has a very specific purpose: to provide data visualization that is easy to use and understand. 

## Deliverable One: Change Trip Duration to a Datetime Format

Using Python and Pandas functions, convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After the "tripduration" column was converted to a datetime dataytpe, the DataFrame was exported as a new CSV file to use for the trip analysis.
![Fig 1 - DataFrame](https://github.com/ASCHEET/Bikesharing/blob/main/Resources/Deliverable-1.png?raw=true)

## Deliverable Two: Create Visualizations for the Trip Analysis
![Fig 2 - Initial Data](https://github.com/ASCHEET/Bikesharing/blob/main/Resources/2-1.png?raw=true)
Tableau has been used to determine the bike rental data for New York City for the month of August 2019.  There is an interest in replicating a similar model for downtown Des Moines, IA.  
Of the analysis for the month of August it collated over 2+ million transactions, and the data was sorted to determine if/how the model can be used in Des Moines.  Here is a quick breakdown of the rental users.  As you can see there is a subscription service for the rental bikes, this shows that more than 75% of users are subscribers to the bike service and most likely use it on a regular basis.  Another observation is that 2/3 of the users are male.  One marketing strategy would be an attempt to market, or make it easier for women to rent or ride bikes that could increase the female demographic.

Figure 3 below shows a map of NYC that shows the highest rental starting locations.  The larger the dot and darker the dot, it corresponds to higher density rentals.  Top three rental starting locations are 
![Fig 3 - 2-2](https://github.com/ASCHEET/Bikesharing/blob/main/Resources/2-2.png?raw=true)

Figure 4 below shows a similar map of NYC that shows highest rental return locations.  The highest density starting are also the highest density rental ending locations.  It would indicate that there is a high concentrations of commuter users that get on and off at the same locations routinely.
![Fig 4 - 2-3](https://github.com/ASCHEET/Bikesharing/blob/main/Resources/2-3.png?raw=true)

Figure 5 below shows that of the 2+ million rentals for the month of August 2019, 146,752 were for a rental time of five minutes.  A total summation of 2+ million rentals shows that 512,864 rentals were for 5 minutes or less.  This is good information showing that users are going relatively short distances and perhaps a pricing strategy could be utilized to take advantage of the high volume of short distance users.  For example, charging a flat rate for the first 5 minutes then charging per unit time (minute) the bike is checked out.
![Fig 5 - 2-4](https://github.com/ASCHEET/Bikesharing/blob/main/Resources/2-4.png?raw=true)

Figure 6 below shows the same data in Figure 5 but it is broken down by gender.  This shows that a majority of the rentals are male.  Some investigation could be performed as to why males are renting 3:1 over females.  It could be due to shoes or clothing that women wear may not be conducive to bicycling.  CitiBike might investigate alterative petals that might benefit different shoe types.
![Fig 6 - 2-5](https://github.com/ASCHEET/Bikesharing/blob/main/Resources/2-5.png?raw=true)

Figure 7 shows a count of popular rental hours sorted by weekday.  The figure below shows that the busiest times during the week are commuting to and from work.  The weekend seems to be less dense bur more consistent.  This can be due to people renting bikes for more leisurely applications vs. rushing to get to work.
![Figure 7 - 2-6](https://github.com/ASCHEET/Bikesharing/blob/main/Resources/2-6.png?raw=true)

Figure 8 displays a count of popular rental hours sorted by weekday and gender.  Both plots are similar but the male plots is more densely populated during the common commuter times.
![Fig 8 - 2-7](https://github.com/ASCHEET/Bikesharing/blob/main/Resources/2-7.png?raw=true)

Figure 9 shows a similar count of popular rental hours sorted by weekday, gender, and if the user is a subscriber.  This plots seems to show most subscribers use the CitiBikes during the weekdays, while non-subscribers use the bikes during the weekends.
![Fig 9 - 2-8](https://github.com/ASCHEET/Bikesharing/blob/main/Resources/2-8.png?raw=true)


## Summary of Results
Overall, males were the primary users of CitiBikes in New York City during August 2019. The most usage occurred on weekdays during expected commuter times, and popular starting and ending locations of Citibike trips were the same. 

In order to determine if Citibikes is a good fit for Des Moines, surveys of downtown metro commuters and weekend users would have to be conducted to determine the main modes of transport. New York City has a very substantial tourist population.  The non-subscriber fares could be a large percentage of tourist rentals.  Additional information would have to be collected to verify, but if Des Moines was looking to replicated they would have to understand a large percentage of revenue would be from a tourist population that does not exist in Des Moines.

Perhaps more of a quantitative approach of analyzing more than one month of data could help identify some more useful trends.  Also, if the analysis could use starting and ending locations to calculate milage per bike as well as, user information as to whom was a high rental user vs the low rental user.
