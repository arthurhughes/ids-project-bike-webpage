On this page we'll have an overview of the data and some analysis.
Firstly, we have a histogram of the entire data set.
![Histogram of Entire Data Set](https://user-images.githubusercontent.com/71314304/96431891-d5c07700-120c-11eb-9084-a44561d969d0.jpg)
Immediately you can see why we believe our tool to be so relevant - on many days during the peak season of each year, over 20000 bikes are rented in the Helsinki area. 
Hundreds of people rely on this service every day for leisure and practical purposes, as a safe, efficient, and eco-friendly way to travel around the capital. 
And the scheme only appears to be becoming more popular, each year the number of rentals increasing from the last. In 2019 there were 3,787,896 rentals, and in June alone, its peak month, there were 715,286 in total.





So now we have an idea of how the rentals vary over the course of a year, let's get a little more specific - how do rentals vary over the course of a day? 
![Composed Plot of Daily Frequency](https://user-images.githubusercontent.com/71314304/96431993-f983bd00-120c-11eb-8750-6e3c2a16b1b4.jpg)
Here we've composed the individual line plot of every individual day in the data set on the same canvas.
You can now see some very clear patterns. There are two obvious peaks at around 6AM and 2PM, suggesting the bikes are being used by commuters. 
These two huge peaks during the day highlight excatly a situation where our tool could be used to good effect. If an individual wishes to commute to or from work during the rush hour, there will certainly be stations in the city where bikes are not available. Our tool would be able to tell that person which station would have the best chance of having an available bike, or, a better time during the day to travel in.
We also can see some kind of "banding" going on. Underneath the stronger two peaks pattern there appears to be a group of days which follow a shallower, single peak. 
Let's try to see this further by turning up the transparency on the plot to highlight only the data which most adheres to the pattern. 
![Modified Daily Frequency](https://user-images.githubusercontent.com/71314304/96432005-fbe61700-120c-11eb-86ed-8fd81490bb38.jpg)
And we can see it more clearly now. So what could be causing this banding effect? If it was caused by outdoor conditions, one would expect less of a discrete pattern due to the large variety in weather conditions. If it was caused by the change in season, one would expect more of a gradual decline in rentals rather than a complete change of pattern. The other obvious possibility is that the pattern of rentals during the day depends on the day of the week.
Let's try splitting the data by the day of the week to verify if this is indeed the case.
![Separated Daily Plot](https://user-images.githubusercontent.com/71314304/96432018-fe487100-120c-11eb-9fed-9db2c94483cb.jpg)



![Average Day Plot](https://user-images.githubusercontent.com/71314304/96432029-00123480-120d-11eb-83e7-a29a6a296f9c.jpg)

