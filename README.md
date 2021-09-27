# Bike Sharing Analysis
Tableau Story: 
https://public.tableau.com/app/profile/colin1753/viz/Bikeshare_16227460584840/BikeshareStory

Trableau Dashboard:
https://public.tableau.com/views/Book1_16225950340940/NYCCitiBike?:language=en-US&:display_count=n&:origin=viz_share_link

## Overview
This analysis of New York City Citi Bike use is meant to create a framework with which to determine if bike sharing business would be viable in Des Moines, Iowa. This analysis is cursory and does not take into account factors related to Des Moines' population, density, financial dmeographics, or competition. In this assessment we will examine ride share data in relation to service type (subscription vs non-subscription), gender, days and times, and locations of use. 

## Results

### Gender:
We can see easily in figure 1 that gender is skewed predominately toward men vs women. 

Fig 1.
![fig1](https://github.com/ghynox/bikesharing/blob/main/bikeshare_pics/genders.png)

### Days & Times:
To begin with identifying peak hours, we can see in figures 2, 3 and 4 that the greatest usage is during the major work traffic timeframes of 7-9am and 4-6pm. Figure 2 shows that as a whole, Monday through Friday work times are highest, however weekends throughout the day also see high levels of use. Figure 3 breaks down by gender to show that the same pattern can be seen between men and women, however the non-gendered data does not hold to the same timeframe. Figure 4 demonstrates that lack of pattern for non-gendered usage could be related to the difference of subscriptions identifying gender and non-subscriptions not identifying gender and being more tourists who use the bikes throughout the day without respect of the work traffic. 

Fig. 2
![fig2](https://github.com/ghynox/bikesharing/blob/main/bikeshare_pics/trips_by_hours.png)

Fig. 3
![fig3](https://github.com/ghynox/bikesharing/blob/main/bikeshare_pics/trip_hours_genders.png)

Fig. 4
![fig4](https://github.com/ghynox/bikesharing/blob/main/bikeshare_pics/trips_by_hour_usertype_gender.png)


### Trip Durations:
In figures 5 and 6 we can see that the durations of bike rentals show a distinct pattern of having a peak duration in the range of 5-6 minutes, but with a median of 11.2 minutes. This means that we have a higher probability of a small number of bikes being rented for extended durations where the majority of rides are commuter rides to and from work using only a short duration. Figure 6 shows that breakdowns by gender repeat the overall pattern and non-gendered data shows a flatter, wider band which again seems to correlate with the non-gendered data being tourists who will use the bikes for longer durations as they explore the city. There are notable outliers related to the data which could be related to errors in billing software or issues with failure to checkout from renting a bike, causing extremely long duration rentals. 

Fig. 5
![fig5](https://github.com/ghynox/bikesharing/blob/main/bikeshare_pics/trip_durations.png)

Fig. 6
![fig6](https://github.com/ghynox/bikesharing/blob/main/bikeshare_pics/trip_durations_gender.png)

### Age:
When assessing the age demographics of those that are using the bikes, we see that we do not have data for individuals under the age of 18. This may fail to show the full picture of the data since there is a likelihood that high school students would use the bikes to get to school or to visit friends across town as an alternative to riding the bus or subway. Given the data that is presented however, we can see that we have a distinct increase in usage based around the 18-25 range vs older customers (Figure 7), and we have some outliers in age that are likely related to users inputting birthdates that are not their own. This could be for privacy purposes, joke purposes (ie a large spike at 1969), or for other reasons, but the probability that people of ages 80 to more than 100 are using bike rentals is extremely low. 

Fig. 7
![fig7](https://github.com/ghynox/bikesharing/blob/main/bikeshare_pics/use_by_age.png)

### Locations:
Assessment of the data showed that the predominant locations for bike rental were in the highest density of work and living space, namely downtown. This was closely followed by the surrounding boroughs. The downtown area of Manhattan is a major tourist center and houses most of the office space in the city, which means that both tourists and commuters are likely to use the bikes in this area. Figures 8 and 9 both show that start and end locations during the highest levels of traffic (7-9am and 4-6pm) are centered on the downtown Manhattan region. 

Fig. 8
![fig8](https://github.com/ghynox/bikesharing/blob/main/bikeshare_pics/start_times.png)

Fig. 9
![fig9](https://github.com/ghynox/bikesharing/blob/main/bikeshare_pics/end_times.png)


### Summary:
The target users for bike rental services seem to fall into two categories, commuters and tourists. Commuters take the lion’s share of the usage. This indicates that a primary location for this service would be in a densely populated area like a downtown where people both live and work and the distance from home to work is able to be biked. A location that also has a higher prevalence of tourism would bolster the business, but with commuters making up such a large percentage of the customer base, commuters must be the primary target. 
 
There are some potential issues related to the data and/or the service that could be identified and addressed to improve viability of this service as well. Based on the trip duration data, there are some very long duration outliers that could indicate issues with software incorrectly calculating trip durations or potentially failing to check users out of their rentals and thus charging them for extensive durations. 

As this relates to DeMoines, Iowa, there is no presented information or data related to the target city that would indicate whether this assessment of usage would carry over successfully to the new city. Researching tourism rates, living density in the downtown areas and surrounding boroughs, and identifying methods of public transit and their prevalence of use would give a much better ability to utilize the given data. While New York City may be a a general comparison as a metropolitan area, it is a less-than-ideal comparison due to the fact that it is by far the most populated city in America, and contains greater than ten times more people than Des Moines and commands a much greater tourism market. This will greatly affect the profitability of the bike share endeavor and should be used to calculate profitability projections. 

*Note: additional visualizations can be found in the genders figure and the two locations figures*
