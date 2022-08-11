# MechaCar_Statistical_Analysis
Assist the data analytics team to perform several analysis including a multiple lineear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.  Additionally collect summary statisticds on the psi of the suspension coils, run t-tests to determine if the manufacturing lots are statistically different from the mean population, and design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.  Lastly a summary of the findings will be provided.

## Linear Regression to Predict MPG
- Based on my analysis the vehicle_weight (0.0776), spoiler_angle (0.3069) and AWD (0.1852) provide non random amount of variance. Additionally it appears the maximum random variance is provided by ground_clearence (5.21e-08) and vehicle_length (2.60e-12).
- At 0.7149, or 71.49%, the R squared value implies that 71.49% of the time the predictions will be correct using a linear model. 71.49% is not high, but also not low.  Generally, the larger the R squared, the better the regression model fits the observations.  An R squared of 0% represents a model that does not explain any of the variation in the response variable around its mean, whereas an R squared of 100% represents a model that explains all of the variation in the response variable around its mean.
- At 5.35e-11, the p-value is less than zero therefore the slope is not equal to zero.

![This is an image](https://github.com/Jahill17/MechaCar_Statistical_Analysis/blob/main/Deliverable1_DataFrame_LinearRegression_SummaryStatistics.png)
