# MechaCar_Statistical_Analysis

## Purpose of this project
The objective of this project is to answer the following questions:-

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Linear Regression to Predict MPG
![Deliverable 1](https://user-images.githubusercontent.com/93144225/155575589-e9cf21d9-b629-4c2d-9d3e-715336cabb46.png)

We must answer the following questions:-
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  * If we look at our **Pr(>|t|)** value for vehicle length and ground clearance (and intercept), provide a non-random amount of variance to the linear model of mpg . We can conclude that their values effect the mpg values.


* Is the slope of the linear model considered to be zero? Why or why not?
  * The p-value of our linear regression analysis is 5.35 x 10^-11, which is smaller than our significance level of 0.05%. As such the linear model considered to be not zero.


* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?  
  * The **R-squared value is 0.71** so 71% of the variations in mpg can be explained by changes in the vehicle length, vehicle weight, spoiler angle and ground clearance. As such, the linear model is effective at predicting mpg of MechaCar prototypes.


## Summary Statistics on Suspension Coils

![Deliverable 2](https://user-images.githubusercontent.com/93144225/155579997-73a4bfbf-c38d-4f71-a6d8-520dda14defc.png)

* Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

  * The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 psi. The design specs for all manufacturing lots in total has a variance of 62.29 psi for the suspension coils. This does not exceed the 100 psi requirement.

  * For Lot 1 and Lot 2 respective variances are 0.98 and 7.47 psi. But for Lot 3 the variance is 170.29 psi, thus it is out of our 100 psi spec.


## T-Tests on Suspension Coils

### Summary of T-Test across all manufacturing lots
![image](https://user-images.githubusercontent.com/93144225/155598749-8607cd05-2e51-4d5a-b888-a8a736491d8d.png)
* Assuming our significance level is the common 0.05%, our p-value (0.06) is above the significance level. As such, we do not have sufficient evidence to reject the null hypothesis and we can state that the two means are statistically similar.


### Summary of t-Test for each manufacturing lot

* **Lot 1**  
![image](https://user-images.githubusercontent.com/93144225/155600051-ddb4a229-51a4-47d8-9908-a067283551f6.png)

The P-value (1) is above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis and we would state that the two means are statistically similar.


* **Lot 2**
![image](https://user-images.githubusercontent.com/93144225/155603479-deee13b6-0a85-4fa6-b141-eedf97aeb01e.png)

The P-value (0.60) is above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis and we would state that the two means are statistically similar.


* **Lot 3**
![image](https://user-images.githubusercontent.com/93144225/155603608-f3df34b9-6963-4553-be1a-3782021cc5ef.png)

The P-value (0.04) is lower than our significance level. Therefore, we have sufficient evidence to reject the null hypothesis and we would state that the two means are statistically different.


## Study Design: MechaCar vs Competition

There are many factors that consumers take into consideration when evaluating a car to purchase. But for this study we will be focusing on safety rating and cost. We can divide the safety rating with the cost to get a safety rating to cost ratio. This can help customers decide on how much to spend on a car according to the cars safety rating. An expensive car can have a better safety rating then a cheaper car and vice versa.

* What metric or metrics are you going to test?
  *  Cost
  *  Safety rating

* What is the null hypothesis or alternative hypothesis?
  * **_Null Hypothesis_**: The average safety value of a mechacar = the population mean value-safety score
  * _**Alternative Hypothesis**_: The average safety value of a mechacar car > the population mean value-safety score

* What statistical test would you use to test the hypothesis? And why?
  * _**One-Sample T-Test**_: We will be comparing against the population mean but will only consider the Mechacar scores that are greater than the population mean. As such we will be using one-sample one-sided t-test.

* What data is needed to run the statistical test?
  * Safety test data from Mechacar and MechaCar prices
  * Average safety test scores for population and average price for population

## Links
  * Visit this [link](https://github.com/tanzimamin2/MechaCar_Statistical_Analysis) for other resources.
   
