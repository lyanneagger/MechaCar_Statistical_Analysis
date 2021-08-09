# MechaCar Statistical Analysis

## Overview

The MechaCar, the newest prototype from AutosRUs, is experiencing production troubles that are hindering the manufacturing team’s progress. This analysis will use Rscripts to review the production data to help the manufacturing team overcome these obstacles.

## Results

## Linear Regression to Predict MPG

Linear regression was performed, with all available variables in the data set: vehicle length, vehicle weight, spoiler angle, ground clearance, AWD, and mpg. The linear regression and summary are shown below. 
- Based on their p-values, vehicle_length and ground_clearance provided non-random amounts of variance to the mpg values in the dataset.
- The slope of the linear model is not considered to be zero, given the small p-value of 5.35e-11, which is much less than the significance level of 0.05. This gives us enough evidence to reject our null hypothesis, which means that the slope is not zero.
- The linear model predicts the mpg of MechaCar prototypes roughly 71% effectively based on the R-squared value of 0.7149. There may also be other factors that contribute to mpg variability that were not included in the dataset.

Linear Regression </br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/1_linear_regression.png "Linear Regression")</br>

Summary of Linear Regression</br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/1_summary_linear_regression.png "Summary of Linear Regression")</br>


## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Analysis for the total and each individual lot are shown below. 
- Analysis of the data for three lots as a whole shows that the coils are within the required ranges, with a variance of 76.23.
- Analysis of individual lots show that Lots 1 and 2 are well below the 100 PSI variance (1.15 and 10.13), which do meet the design specifications.
- However, Lot 3 is showing a much higher variance of 220.01, which does not meet the design specifications.

Total Summary</br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/2_total_summary.png "Total Summary")</br>
Lot Summary</br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/2_lot_summary.png "Lot Summary")</br>


## T-Tests on Suspension Coils

![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/3_ttest1.png)</br>
This T-Test was performed on a sample of 50 coils to determine if the PSI across all manufacturing lots is statistically different from the overall population mean of 1,500 PSI. The p-value 0.81, which is above the assumed significance level of 0.05 percent. This shows that there is not sufficient evidence to reject the null hypothesis and that the two means are statistically similar.

T-Tests were also performed on each of the 3 lots to determine if the PSI for each is statistically different from the population mean of 1,500 PSI. 
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/3_ttest_lot1.png)</br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/3_ttest_lot2.png)</br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/3_ttest_lot3.png)</br>



## Study Design: MechaCar vs Competition

One study that can be performed that can quantify how the MechaCar performs against the competition would compare key metrics. For this study, we would compare fuel efficiency, cost, and safety rating.

The null hypothesis is that MechaCar performs similarly to competitors for fuel efficiency, cost, and safety rating.

A two-sample T-Test can be performed to determine how the mean performance for MechaCar compares to the overall population including all competitors. This would determine if the means are statistically similar and show how MechaCar performs against competitors in each category.

To run the statistical test, data would need to be provided from different competitor car models with the details of their fuel efficiency, cost, and safety ratings. The input data should be normally distributed and would provide greater insight if the dataset is large.




