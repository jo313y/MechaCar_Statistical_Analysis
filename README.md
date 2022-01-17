# MechaCar_Statistical_Analysis
R analysis

## Linear Regression to Predict

Looking at the above statistical analyses it can be shown that the vehicle_length, ground_clearance, and vehicle_weight provided non-random amount of variance in the mpg values. The intercept provide a non-random aount of variance as well, which means the data may need to be transformed or there is another variable that was not used in this model.

Looking at the intercept, the slope of the linear model is  not considered to be zero. The value is -1.04e+2, which is a non-zero, negative value. The intercept not on the zero mark is another indicator that the analysis may have missing data. This can sometimes indicate a bias in data depending on the analysis. In this case, it is important to look at the actual values of the intercept.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This linear model fits the data for mpg of the MechaCar prototypes well. The R-squared value is 0.71, which is a positive correlation with this model. 
Furthermore, the p-value is significant, meaning we can reject the null hypothesis. However, due to the significance of the intercept and it's non-random association with the data, the model will most likely not be useful when predicting future trends. 

Below is the raw data from the Linear Regression.
![MechCarMPGStats](https://user-images.githubusercontent.com/86981530/149685383-8469805e-12d4-4473-b697-cc7f7d6dba00.PNG)


## Summary Statistics on Suspension

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. On average, the variance in around 63 PSI change. This is within the acceptable limits. 

![total_summarytable](https://user-images.githubusercontent.com/86981530/149685395-c03ed801-4469-451d-88bd-b43c41512f46.PNG)


When we break down the statistics based on each Lot, however, Lot 3 has a variance of over 100 PSI in its suspension coils. This is not in accordance with the design specifications.

![Lot_Summary](https://user-images.githubusercontent.com/86981530/149685398-0aca8a41-9ef8-4e05-8657-50d363f29553.PNG)


## T-Tests on Suspension Coils

The population mean of the PSI for the suspension coils is 1500 PSI. The average for Lot 1, Lot 2, and Lot 3, respectively, are 1500, 1500, and 1498 PSI.
The population mean was compared to the Lots and it was determined that there was no statistical differences. They are essentially the same number. It was compared across each lot. 

![TTest](https://user-images.githubusercontent.com/86981530/149687513-905881d4-3dd3-4ae7-83cd-7a689b6c015d.PNG)

## Study Design: MechaCar VS Competition

It is important to design and test the MechaCar against known competition. A valuable metric to compare agains is to compare the mpg from each lot vs the average mpg of the competition. This would test to see that the design changes in this vehicle have helped it increase it's mpg (alternative hypothesis). 

In order to compare the mpg across all Lots and IDs, it would be important to use the p-values, as well as the t.test. The p value can be split between different options on the car to determine if it has made a statistically significant change in the mpg. For instance, if the suspension PSI affects the mpg. 

The Lot with the highest mpg can then be compared to the competitions mpg to determine who has a higher rating. This can be statistically analyzed using the t.test for empirical data. 
