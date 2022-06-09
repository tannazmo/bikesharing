# bikesharing


Tableau Public file is available by clicking [My Tableau Public Story](https://public.tableau.com/app/profile/tannaz.mostaghimi/viz/Module14_Challenge_16547398741490/TheStory?publish=yes)



## Overview of the analysis: 
The main purpose of this analysis is to analyse the bike sharing system (citi bike) in NYC and see what we can learn from the data in order to show the investors that the same business model would work in Des Moines and they should invest in implementing the same model.


## Results: 
Below you can see the story points in the Tableau Story using the NYC data:

### *1. Checkout Times for Users*
![Story Point 1](/images/StoryPoint1.png "Checkout Times for Users")
This visualisation shows the length of time the bikes are rented by users. Most bikes are returned under one hour and most being returned within half an hour.

--------

### *2. Checkout Times by Gender*
![Story Point 2](/images/StoryPoint2.png "Checkout Times by Gender")
To furthur narrow down, we will look at the gender of the riders, it shows the number of men who returning the bike within 10 minutes are about three times of women. We should also look at the proportion of renters in general, for each gender [here](/images/Del3_Gender.png) which shows the consistency.

--------

### *3. Trips by Weekdays per Hour*
![Story Point 3](/images/StoryPoint3.png "Trips by Weekdays per Hour ")
This heatmap shows the times of days when are there more activities. This confirms that during the week, the morning rush hour is between 7am and 9am and in the afternoon between 5pm and 7pm. It also shows that for weekends it gets relatively busy starting at 9am and getting busy, but steady and it relatively quiets down by 9pm. 

--------

### *4. Trips by Gender (Weekday per Hour)*
![Story Point 4](/images/StoryPoint4.png "Trips by Gender (Weekday per Hour)")
Looking at the same type of chart, but this time separating the genders, shows that in general the same pattern of rush hour renting and returning is followed no matter the gender, the only difference is the number of male riders are more than female riders (reflected in the heat map) which is still consistent with the original pie chart showing the proportion of male/female riders. 

--------

### *5. User Trips by Gender by Weekday*
![Story Point 5](/images/StoryPoint5.png "User Trips by Gender by Weekday")
This heatmap is showing the ride count of Subscribers vs random Customers by weekday and by gender.

--------

### *6. Top Starting Locations*
![Story Point 6](/images/StoryPoint6.png "Top Starting Locations")
This additional story point was included to show which parts of NYC is more active in terms of citi bike rides. It shows which stations are more popular as a starting point for renters.

--------

### *7. August Peak Hours*
![Story Point 7](/images/StoryPoint7.png "August Peak Hours")
This additional story point shows the peak hours recorded in the month of August, I have highlighted the peak hours which are during the morning and afternoon rush.


## Summary: 
In the following image, we can see three visualisations, that we can determine the age range and gender of the riders in NYC:

I created a calculated field for Age Range and created two visualizations off of it:
One showing The number of rides taken by each age range, which indicates that more than 50% of the riders are between 20 and 40 years old.

The other showing the heatmap of the ridership among different genders.

![Dashboard for Gender and Age](/images/Del3_Dashboard.png "Age & Gender of Riders")

My first suggestion was to create an age range field and create visualisation based on that which I did myself.

I would also suggest creating visualisations showing the trip duration based on Age Range and Gender for further analysis.
