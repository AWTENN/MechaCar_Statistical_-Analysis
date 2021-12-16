# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG



- In the linear regression model of the MechaCar dataset, the vehicle length, ground clearance, and intercept variables had the most non-random amount of variance to the mpg values.
- The slope of the linear model is not zero because the p-value of the regression is much smaller than our assumed significance.
- The model predicts this data set very well, because the r-squared value is 0.7149 meaning that 71.49% of the variability of MPG can be predicted using this model. However, this model could be overfit on this dataset, so I believe we would need more data of a length of time to get a more accurate model.

## Summary Statistics on Suspension Coils



- The design specifications of the variance of suspension coils not exceeding a variance of 100 pounds per square inch is not met by all lots. Lot 3 has a variance of 170 pounds per square inch which is very much over the variance limit that is set by the company.

## T-tests on Suspension Coils







- In the t-tests on the Suspension Coil Data, I found that the entirety of the Lot data is barely statistically similar to the population mean of 1500 PSI. Lot 1 and Lot 2 are both similar to the population PSI, but Lot 3 is statistically different from the population PSI.

## Study Design: MechaCar vs. Competition

- For a study of how MechaCar does against its competition, I would like to look at Highway MPG and Maintenance Cost.
- Null Hypothesis: The difference between MechaCar and their competition’s highway mpg and maintenance are equal 0 for both.
- Alternate Hypothesis: The difference between MechaCar and their competition’s highway mpg and maintenance are not equal 0 for both.
- I would use a two-sample t-test to compare the two datasets and see if there are statistically significant differences between MechaCar and their competition.
- We would need the mean, standard deviation, and sample size for both datasets of MechaCar and their competition.

