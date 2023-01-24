# CitiBike Analysis

## Overview and Purpose of Project
The Analyst took a trip to trip to New York City with their friend, Kate, where they hatched an idea to replicate the bike sharing system CitiBike in their home city of Des Moines Iowa.  With a potential angel investor ready to turn the teams dream into a reality, the Analyst had to turn to the NYC CitiBike data to analyze certain trends and get a better understanding on how the general public used this product.  Using data sets from CitiBike's system data page, python, and tableau, the Analyst was able to visualize data and gain a better understanding on consumer use patterns that can later be applied to the team’s business opportunity in Des Moines.

## Link to the Tableau Analysis
[Tableau Story](https://public.tableau.com/shared/RHZG2ZYJN?:display_count=n&:origin=viz_share_link)

## Analysis and Results
After the Analyst used python to organize and clean the raw CSV data, they utilized Tableau to create their visualizations.  The visualizations and analysis are below:

### Peak Bike Usage Times
The visualizations below break down different CitiBike ride metrics into total number of rides per hour over the course of the month August, number of trips by weekday per hour, and number of trips by weekday per hour for each gender.

![Peak_Times.png](https://github.com/hillmanj1995/bikesharing/blob/827799e691d28cd439db7f887aec843e6fbbc5d2/Resources/Peak_Times.png)

Looking at the number of rides per hour and trips per weekday per hour analyses, it is apparent that the peak times for CitiBike riders are during the rush hour periods of around 7AM to 10AM and 4PM to 7PM.  The trips per weekday per hour visualization shows further shows that rush hour has the busiest traffic cycles for CikiBike, and the that during the weekend, the number of riders is much more uniform throughout the day instead of having two distinct peaks.  To further break the data down, similar patterns are shown when looking at the number of trips by weekday per hour for each gender.  The visualization shows that there are more male riders than female and unknown (gender) riders.

### Bike Checkout Duration
The Analyst created plots to visualize the CitiBike trip durations to best show the amount of time people are spending on the bikes.  They provide a plot that shows the trip duration for the total number of bikes over the course of the month of August, a breakdown of the customer genders, and a visualization of the trip duration by gender.

![Checkout_times.png](https://github.com/hillmanj1995/bikesharing/blob/44d9d0474f0163642e5f43bdb619b2797251f331/Resources/Checkout_times.png)

Looking at the Checkout Times for All Users plot, it shows that most rides lasted between 5 and 6 minutes.  After about a 6-minute ride duration, the number of rides steadily decreased.  This trend was further proven in the Checkout Times by Gender plot that showed peaks of ride duration usually between 4 and 7 minutes for male and female riders.  Unknown (gender) rider data did have a definitive peak.  It showed a fairly constant number of riders for ride durations spanning from 0 to 35 minutes.  The breakdown on the number of customers by gender was also provided for reference.

### Top Starting and Ending Locations
Since NYC is large metropolitan area, the Analyst provided plots to illustrate the most popular starting and ending bike rental stations.  Those visualizations are below:

![Starting_Ending_times.png](https://github.com/hillmanj1995/bikesharing/blob/44d9d0474f0163642e5f43bdb619b2797251f331/Resources/Starting_Ending_times.png)

The plots show a similar trend of southern Manhattan being the most popular area to rent CitiBikes, with some popular stations in Brooklyn and Queens.  Furthermore, the larger the distance from Manhattan seems to correspond to a lower count of bike rentals.

## Summary 
The Analyst was successful in providing a comprehensive visual analysis of the NYC CitiBike data that showed customer riding tendencies and breakdown of those patterns by gender.  The analysis showed that the majority of the CitiBike consumers were located in the southern half of Manhattan, rode primarily for 4 to 6 minutes during the rush hour periods of 7AM to 10AM and 4PM to 7PM.  

It was also apparent to the Analyst that the vast majority of CitiBike's consumer base was male.  To see if the gender discrepancy varied by location, the Analyst did an analysis of the top starting and ending CitiBike locations by gender.

![Starting_Ending_times_gender.png](https://github.com/hillmanj1995/bikesharing/blob/44d9d0474f0163642e5f43bdb619b2797251f331/Resources/Starting_Ending_times_gender.png)

Although the visualization provided a breakdown of where different genders rent more bikes, it did not show much any unexpected results that weren't already shown in the previous analyses (ex. More women than men and unknown (gender) renting bikes in Brooklyn, etc...).  

Moving forward to Kate and the Analyst's business plan, they should focus on finding a way to appeal to female clientele as currently it seems like CitiBike is male dominated bike share program.  Appealing to a wider array of clients has the potential to make CitiBike "stick" better in Des Moines and provide a better return on investment for the angel investor by increasing bike rentals. 
