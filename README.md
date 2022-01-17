# MechaCar_Statistical_Analysis
R analysis

## Linear Regression to Predict

![MechCarMPGStats](https://user-images.githubusercontent.com/86981530/149685383-8469805e-12d4-4473-b697-cc7f7d6dba00.PNG)


Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
the intercept, vehicle_lenth, ground_clearance, and vehicle_weight provided non-random amount of variance in the mpg values. The intercept provide a non-random aount of variance as well, which means the data may need to be transformed or there is another variable that was not used in this model. 

Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not considered to be zero. The value is -1.04e+2, which is a non-zero value. The intercept not on the zero mark is another indicator that the analysis may have missing data. 

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This linear model fits the data for mpg of the MechaCar prototypes well. The R-squared value is 0.71, which is a positive correlation with this model. 
Furthermore, the p-value is significant, meaning we can reject the null hypothesis.

However, due to the significance of the intercept, this means there are variables missing which means this model will most likely not be useful when predicting trends. 

## Summary Statistics on Suspension

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

![total_summarytable](https://user-images.githubusercontent.com/86981530/149685395-c03ed801-4469-451d-88bd-b43c41512f46.PNG)


![Lot_Summary](https://user-images.githubusercontent.com/86981530/149685398-0aca8a41-9ef8-4e05-8657-50d363f29553.PNG)

## T-Tests on Suspension Coils

![TTest](https://user-images.githubusercontent.com/86981530/149687513-905881d4-3dd3-4ae7-83cd-7a689b6c015d.PNG)
T Test across all manufacturing lots and for each lot




