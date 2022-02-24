# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![Deliverable 1](https://user-images.githubusercontent.com/93144225/155575589-e9cf21d9-b629-4c2d-9d3e-715336cabb46.png)


We must answer the following questions:-
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  * If we look at our **Pr(>|t|)** value for vehicle length and ground clearance (and intercept), provide a non-random amount of variance to the linear model of mpg . We can conclude that their values effect the mpg values.


* Is the slope of the linear model considered to be zero? Why or why not?
  * The p-value of our linear regression analysis is 5.35 x 10^-11, which is smaller than our significance level of 0.05%. As such the linear model considered to be not zero.


* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?  
  * The **R-squared value is 0.71** so 71% of the variations in mpg can be explained by changes in the vehicle length, vehicle weight, spoiler angle and ground clearance. As such, the linear model is effective at predicting mpg of MechaCar prototypes.


## Results
These are our findings.

### Checkout Times for Users
![image](https://user-images.githubusercontent.com/93144225/154584203-c26b0919-cbb8-40a4-96ff-25615bfb40ee.png)

As the graph shows, most of the bikes were used for a duration of 20 mins or less.

### Checkout Times for Gender
![image](https://user-images.githubusercontent.com/93144225/154585920-84275b6c-7039-47ff-af08-c1cf34f55fc0.png)

This graph shows us bike usage times based on gender.

### Trips by Weekday per Hour
![image](https://user-images.githubusercontent.com/93144225/154586783-3281d592-e186-4e6a-b56b-8bdf0801a3cf.png)

Weekdays from 6am to 9am and in the evening from 5pm to 7pm, we have highest bike usage. Whereas in the weekend 10am to 6pm is our busiest time.

### Trips by Gender (Weekday per Hour)

![image](https://user-images.githubusercontent.com/93144225/154588152-f0f55c2d-1f46-44fe-81ec-06194ac73906.png)

This heatmap shows high demand times by gender during the days of the week and by hour of the day. We can conclude that males are renting more at the high demand times versus females.

### User Trips by Gender by Weekday

![image](https://user-images.githubusercontent.com/93144225/154592253-e6353500-5d33-4fdf-92df-f2d55fd5eb7b.png)

This graph shows the number of trips by weekday, by user type (subscribers versus customers) and by gender. In the subscriber category, males have higher number of trips compared to females.

### User types

![image](https://user-images.githubusercontent.com/93144225/154593541-40e44a2b-0c79-4418-8ce7-bae98be6d35c.png)

This pie chart shows our user types (subscribers versus customers).

### Riders by Gender

![image](https://user-images.githubusercontent.com/93144225/154593651-d4029384-f831-44b6-be95-0eab20bbc28b.png)

This pie chart shows our riders by gender.


## Summary

From our analysis, we can conclude the folowing:-

* Most of the rentals happen during the weekday around normal work commute times (6am to 9am). This is very important as it shows that there is a need for transportation. If we focus on these times we can have a recurring source of revenue as well as customers.
* Our customer base mostly consists of men, it would be beneficial if we market our business more towards the female demographic. This would help us get more customers
* As seen on our User type graph above, we can see that we have more subscribers versus customers. A good portion of our customers have become subscibers, if we provide more perks and lower costs more of our one time customers will convert to subscribers. This will provide us a sustainable source of revenue.

## Links
  * Visit this [link](https://github.com/tanzimamin2/Bikesharing) for other resources.
  * Tableau Public [link](https://public.tableau.com/app/profile/tanzim.amin/viz/bikesharing_16451367548010/CheckoutTimesforUsers#1)
   
