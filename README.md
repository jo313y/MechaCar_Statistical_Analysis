# MechaCar_Statistical_Analysis
R analysis

## Linear Regression to Predict

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
the intercept, vehicle_lenth, ground_clearance, and vehicle_weight provided non-random amount of variance in the mpg values. The intercept provide a non-random aount of variance as well, which means the data may need to be transformed or there is another variable that was not used in this model. 

Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not considered to be zero. The value is -1.04e+2, which is a non-zero value. The intercept not on the zero mark is another indicator that the analysis may have missing data. 

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This linear model fits the data for mpg of the MechaCar prototypes well. The R-squared value is 0.71, which is a positive correlation with this model. 
Furthermore, the p-value is significant, meaning we can reject the null hypothesis.

However, due to the significance of the intercept, this means there are variables missing which means this model will most likely not be useful when predicting trends. 
