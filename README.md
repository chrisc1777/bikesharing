# bikesharing

## Overview
Citibike is a bike-sharing service that provides a convenient commuting option for tourism in New York City. This project involves analyzing Citibike's data to prepare a business proposal for a bike-sharing system in Des Moines. By taking a bike-sharing dataset from August 2019 in New York City, we can manipulate the data using Jupyter Notebook and utilize Tableau to make insightful visualizations for potential investors. 

## Results
[Link to Tableau Story](https://public.tableau.com/shared/P3DWY4YXW?:display_count=n&:origin=viz_share_link)

### Checkout Times for Users
This line graph shows how much time bikes were checked out. Although some bikes are checked out for several hours, most bikes are returned within five minutes of being checked out.

![1](https://user-images.githubusercontent.com/106359564/220800749-ba3d20dd-a355-4436-ac66-5bcba6dea244.png)


### Checkout Times by Genders
We categorized the bike checkout hours by gender. There are more male riders than female riders but since there are 108,087 unknown gender values,  we can't classify a significant difference between male and female riders.

![2](https://user-images.githubusercontent.com/106359564/220800756-aeddba5f-7305-4811-8c14-87f83cdb46f8.png)


### Trips by Weekday for Each Hour
This heatmap shows the relationship between start-time and stop-time by hours. The busiest checkout times occur from 5 pm - 6 pm during the week having over 32,000 checkouts per hour. The busiest day occurs on Thursdays having over 43,000 thousand checkouts per hour. The least busy times occur from 3 am - 4 am on weekdays having less than 900 checkouts per hour. 

![3](https://user-images.githubusercontent.com/106359564/220800771-1b1c63a6-97bb-46cd-8177-601416f9001f.png)


### Trips by Gender (Weekday per Hour)
The heatmap now has gender attributes. We can see similar results during busy hours, but males have more bike usage than females and unknown genders. On Thursdays from 5 pm - 6 pm, males have over 30,00 checkouts.  Significantly different compared to 10,500 checkouts for females and 2,800 checkouts for unknown genders.

![5](https://user-images.githubusercontent.com/106359564/220800791-aa619af7-d0d1-4d21-988b-fd93f5fcd552.png)


### User Trips by Gender by Weekday
In this heatmap, we filtered the checkout times by days instead of hours. We can see that males have more bike usage overall throughout the week. Males have 259,316 checkouts while females have 88,281 checkouts and unknown genders have 6,082 checkouts on the busiest day.

![6](https://user-images.githubusercontent.com/106359564/220800799-6cb0e948-fa71-494d-9f2f-4088a8a8da57.png)


### User Type by Gender
This bar graph shows the user types by gender. We can see that there are far more subscribers than regular customers. The customer base has a majority of unknown genders with 191,515 bike checkouts. Male subcribers have 1,372,601 checkouts compared to 439,752 female subscribers and 34,006 unknown subscribers. 

![7](https://user-images.githubusercontent.com/106359564/221073667-505d6aa1-19bd-4c28-9cf3-a3de89014a3c.png)


### Birth Year by Gender
This line graph shows bike users by gender and birth year. The most popular bike user birth year is 1969 having 207,638 checkouts, but their gender is unknown. From the data we available, most male users were born 1990  with 71,334 checkouts and most female users were born in 1989 with 31,801 checkouts.

![8](https://user-images.githubusercontent.com/106359564/221073675-e14c74af-1f67-4add-aab3-ca484d4e5306.png)

## Summary
Analyzing the bike-sharing data from New York City gave us a lot of meaningful insight into service operations and demographics. We were able to find the duration of checkout times, determine the busiest time of days, customer and subscriber base comparison, and find the most popular age groups. This valuable will help build a strong proposal for a bike-sharing business in Des Moines

