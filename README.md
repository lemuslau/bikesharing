# Bikesharing with NYC CitiBike 

## Overview
The CitiBike Analysis story can be found [here](https://public.tableau.com/views/Module14Challenge_16594058840770/NYCCitibikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) 

The drive for this project was to analyze bikeshare data from CitiBike in New York City for investors with the data provided. This analysis used New York City as the main frame of data, it is intneded to provide visualization for key factors to identify areas of opporunity for launching a bikehsharing program in Des Moines, Iowa. 

These were the main questions essential for visualiation for investors:  
1. Who uses bikeshare programs?
2. What area of a city sees the most bikeshare usage?
3. What time of day are bikes used the most and the least?
4. How much are the bikes used and by whom?

##Results

###NYC CitiBike Customer Description 

![Customer and Gender](https://user-images.githubusercontent.com/102635884/184520200-1eb6752a-0269-4e06-aeca-4a3700f87ccd.PNG)

Undertanding user demographics is essential in understanding who will be subcribing to a bikisharing prgram. Tweo factors in dempographics that were accessible through the CitiBike day was Gender and User Type. In the pie charts below, investors would be able to identify that roughly 2/3 of the customer group in NYC were Subscriibers, which shows that more people were willing to regularly use the bike sharing program.  For gender, roughly 2/3 of the group were main, showcaseing that currently the bike sharing program has a larger pull from the bikesharing program.

### NYC CitiBike Trip Duration

![Checkout Time for Users](https://user-images.githubusercontent.com/102635884/184520866-388e6a1d-f6cf-40c1-b105-55df1775563b.PNG)

Through this lien graph an investor is able to idenitfy that the number of trips by durations had a larger prorpotion of customers using the bikes for less than an hour in lenth. More bike rides were saround a half hour or less. This means that customers most likely traveling short distances. 

### NYC CitiBike Trip Duration by Gender

![Checkout Times by Gender](https://user-images.githubusercontent.com/102635884/184520960-d89a7b09-3219-4067-9eb5-a60973901b2c.PNG)

Similar to the pie chart showing customer usuage by gender, this line grapgh compares trip duration by gender. This grapgh shows that both genders utilized the CitiBikes for less than an hour and neither of the three groups used it more than the other despite the significant customer gender difference.

### NYC CitiBike Peak Use Hours

![Trips by Weekday per Hour](https://user-images.githubusercontent.com/102635884/184520473-178f5ba4-ec8f-48d7-8c4d-1e075fd842ad.PNG)

This heatmap can provide a visualization for weekly usage patterns to identify hours in a day where there is a higher usage in the program. The heaviest bike usage is around typical commuting times Monday through Friday. These time are most frequent around 6am-9am and then again from 4pm-7pm. During the weekends Saturdays saw consistent high usage between the hour of 9am to 7pm which can combine with the evenings where tourst and locals would use the bikes to avoid the traffic in the streets. Additonally, a low usage point is Wednesday evenings where you do not see high usage like you would the other Weekdays. It would be worth exploring this time to see what drives this abdnoramality.

### NYC Citibike Trips by Gender, Weekday, Gender

![Trip by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/102635884/184521100-ed75b9c0-40c6-49ec-8d64-aa4fbeb67146.PNG)

While the last line chart showed us that the duration of most drips were less than an hour by length this next graph shows the times of the day where each gender group uses the bikes the most. Through this analysis, for females eveb with the small usuage by this group, there is no obvious differnce in the times of day that it us used. There is a higher usuage around commuting times but it is not drastically significant of a differnce. For the males, there is a difference based off the heatmap on the times of high usuage. This can be used to confirm that a majority of males using the bike sharing program use it for their commutes, which is most likely within a half hour time span as suggested by the chart above. 

### NYC CitiBike Trips by User Type, by Day, by Gender

Lastly, this heatmap reinforces how much of the userbase is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.

There are one or two additional charts available in the Tableau analysis, but they tell pretty much the same story that has already been displayed above.


NYC CitiBike Top Trip Starting Locations

The above map displays the bike stations from which recorded bike trips started. The size of the circles and darkness of the green indicate the relative number of trips started at those locations. It is apparent that the bulk of the bike trips are originating in the bustling commercial heart of Lower Manhattan, known for towering office buildings, densely packed residential skyscrapers, and entertainment venues. Bike usage is lower in the less densely packed surrounding neighborhoods.

NYC CitiBike Total Rides by Time of Day

This chart displays the number of bike rides initiated during each hour of the day, totaled across the entire month of August. We can see peak usage during morning rush hour and end-of-workday commute times. What is also of note is the low-usage hours between 2 AM and 5 AM. These hours would be the best times to conduct bike repairs and redistribution of bikes from full stations to less-full stations.

NYC CitiBike Bike Usage Spread

To see what proportion of the bikes get heavy usage, we can look at this stepped-level heatmap. This tiling shows each individual bike in the fleet, sized, colored, and sorted by its degree of usage during the month. In red we can see a small number of bikes that get heavy usage, which will require more regular repair, or possibly even replacement. In shades of green, we can see all the other bikes that get much lower levels of use, and will probably not need to be repaired as often.

NYC CitiBike Avg. Trip Duration by Birth Year

This charting of average trip duration by birth year shows two things:

the bikeshare userbase covers all age demographics, from teenagers to nonagenarians (and older);
teenagers and early-twenty-somethings enjoy taking much longer bikerides than older users.


Summary

Subscribers take time 

push for female, pull for male

In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:

trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.
