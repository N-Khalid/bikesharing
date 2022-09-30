# bikesharing

## **Background**

Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## **Purpose**

The purpose of our analysis is to determine if the bikeshare business will be successful in New York City using Tableau visualizations

## **Results**

Link to the Tableau Story: [https://public.tableau.com/shared/F596WQNX3?:display_count=n&:origin=viz_share_link](https://public.tableau.com/views/Unit14Challenge/Story?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

### Top Starting Locations

![Top Starting Locations](https://user-images.githubusercontent.com/103234661/193259997-0bf8f868-853b-40b1-b2a0-b6af2f37ce55.png)

All non-blue circles are ideal places to start a bike ride. The single best area is the deep red circle located at these coordinates (40.7519, -73.9777).

### Top Ending Locations

![Top Ending Locations](https://user-images.githubusercontent.com/103234661/193259981-a7e611c4-864a-467d-ad5c-95cf53021596.png)

All non-blue circles are ideal places to end a bike ride. The single best area is the brown circle located at these coordinates (40.7519, -73.9777). Both the best starting and best ending locations are nearly identical. 

### Checkout Times for Users 

![Checkout Times for Users Viz](https://user-images.githubusercontent.com/103234661/193243619-18d00e57-36e0-4513-a3d2-a9124cde9713.png)

Most bike rides are between 5-10 minutes that will slowly decrease over the course of an hour. Bike rides past an hour are nearly non-existant.

### Checkout Times by Gender 

![Checkout Times for Genders Viz](https://user-images.githubusercontent.com/103234661/193246370-92de1116-d4dc-4d22-a851-232156cb441d.png)

Males will check out the bikes far more often than females at every duration of bike ride.

### Trips by Weekday for Each Hour 

![Trips by Weekday for Each Hour Viz](https://user-images.githubusercontent.com/103234661/193250435-409faca8-346e-4bdc-a054-72149c37e073.png)

More bike rides happen during the weekdays than during the weekends. During the weekdays, people will ride the bikes getting to and from work (early mornings and evenings). During the weekends, there are less overall rides and the spread of rides are from between 10AM to 7PM. 

### Trips by Gender (Weekday per Hour) 

![Trips by Gender (Weekday per Hour) Viz](https://user-images.githubusercontent.com/103234661/193255440-2ea43ece-08f4-448e-8450-3408823e9c31.png)

Both males and females will ride bikes are identical times however there are far more male bike riders than female.

### Trips by Gender by Weekday

![User Trips by Gender by Weekday Viz](https://user-images.githubusercontent.com/103234661/193255803-6b84e124-cbb3-4d09-9c4f-3c30b4d2c887.png)

Due to sheer volume, every weekday will have far more male bike riders than female.

## **Summary**

- The best starting locations are identical to the best ending locations for bike rides
- There is a large majority of male bike riders versus female bike riders
- The weekdays peak bike riding hours are in the early mornings and evenings when many people are commuting to work
- The weekends peak bike riding hours are spread throughout from the late morning to late afternoon likely for leisure rather than commuting

Two additional visualizations that I would suggest for future analysis would be:

1. Checkout times by weekday and weekends
2. Checkout times and total trips per age group within each gender
