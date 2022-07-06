# bikesharing

## Overview
This Tableau story can be viewed [at this link](https://public.tableau.com/app/profile/ashleigh.bridges/viz/bikesharing_challenge_16568846352430/Bikesharing).

The purpose of this project was to analyze CitiBike data from New York City to use in a presentation to investors to start a similar program in Des Moines, IA. In this analysis, we aimed to create visualizations to show the following:
```
- The length of time that bikes are checked out for all riders and genders
- The number of bike trips for all riders and genders for each hour of each day of the week
- The number of bike trips for each type of user and gender for each day of the week
```

## Results
Visualizations created from the NYC CitiBike data are below: 

#### *Trip Start Times by Weekday*
![Trip Start Times by Weekday](https://user-images.githubusercontent.com/100883212/177433848-d3797998-3225-4696-bc96-8a15d8b58ae2.png)

This visualization shows that the majority of weekday trips take place before 9am and after 5pm, during times most people are commuting to and from work. It is highly likely that these are NYC residents who live and work in the city full time. ON the weekends, the majority of bike activity takes place from 10am to 4pm, which is when most people are out running errands or meeting friends. This is also when tourists visiting the city are most likely to be out and about.

#### *Trip Duration*
![Trip Duration](https://user-images.githubusercontent.com/100883212/177433529-7145d846-023d-46d5-9870-fe9d6f8ef921.png)

This visualization shows that the vast majority of trips take around five minutes. After the five minute mark, there is a steep dropoff and the curve finally begins to flatten out around the 40 minute mark.

#### *Checkout Times by Gender*
![Checkout Times by Gender](https://user-images.githubusercontent.com/100883212/177433554-dd89773b-2b8b-4c50-8b31-749a366b0af9.png)

This visualization shows that the majority of users are male (~110k), followed by female (~34k). Both of these groups follow the same trend as the visualization abovee, peaking at around five minutes for the total trip duration. However, users with an unknown gender status (~8k) seemed to take longer trips as evidenced by the flatter curve. The number of these users taking trips that lasted ~5 minutes was about the same as all of the users taking trips that lasted up to ~25 minutes. This could be because users such as tourists who only use the CitiBikes once or twice during their trip are less likely to subscribe and put time into filling out their profiles.

#### *Trip Start Times by Gender*
![Trip Start Times by Gender](https://user-images.githubusercontent.com/100883212/177433609-2ce8f6b3-0487-4d78-ad2b-43d9d70d852d.png)

This visualization is similar to the *Trip Start Times by Weekday* chart listed above, but broken out by gender. As you can see, the trends we have seen in the charts before this are still holding true with the majority of trips occuring during normal weekday commuting hours.

#### *Trips by Gender by Weekday*
![Trips by Gender by Weekday](https://user-images.githubusercontent.com/100883212/177433624-d457f874-4b8b-46a0-8060-ff50ed07bd22.png)

This visualization shows which days have the heaviest bike usage both by gender and by user type. Keeping true to previous observations, the majority of the users with an unknown gender status are Customers, not Subscribers. The heaviest usage days for Customers are on the weekends, when those who do not use the bikes on a regular enough basis to purchase a subscription are more likely to be traveling and use the bikes. For the subscribers, males take the most trups by far, and utilize the bikes more during the weekdays than on weekends, likely for commuting to and from work.

#### *Top Starting Locations*
![Top Starting Locations](https://user-images.githubusercontent.com/100883212/177433636-795953b8-5791-4bfa-9b28-abaaa6c5ff7b.png)

This visualization shows that most of the trips take place on the lower half of the island, in areas where more tourists are likely to be as well as NYC residents who are more likely to utilize a form of public transport as opposed to a private car service or taxi, which would be more common on the Upper East and West Sides due to the higher levels of wealth in those areas.

#### *Bike Utilization*
![Bike Utilization](https://user-images.githubusercontent.com/100883212/177433650-9fc945b0-aadc-49dc-b376-86520f56710e.png)

This last visualization shows how many trips each bike individually has taken. Being able to pull this information together easily is important to be able to predict which bikes will need maintenance more often than others due to higher utilization.

## Summary
As evidenced by our seven visualizations, there were a few conclusions we were easily able to draw that held true throughout the analysis. For example, multiple visualizations showed that the highest times of utilization were before and after the 9-5 workday on weekdays when people are most likely commuting. The data also showed that users mostly check out bikes for short trips - around 5 minutes on average. However, users without a gender status notated in the app (mostly non-subscribers) tend to use the bikes for longer trips - anywhere from 5 to 40 minutes.

If I were to conduct additional analysis given the data provided, I would also create these two visualizations to add to this report:
- A visualization showing usage by month to see if weather/tourist seasons had any effect on usage
- Data categorized by the weather for that day, to see if harsher conditions (rain, snow, etc.) led to lower usage than on days with nicer weather
