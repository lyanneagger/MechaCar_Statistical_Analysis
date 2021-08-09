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
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/1_linear_regression.png)</br>

Summary of Linear Regression</br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/1_summary_linear_regression.png)</br>


## Summary Statistics on Suspension Coils

![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/2_total_summary.png)</br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/2_lot_summary.png)</br>

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

## T-Tests on Suspension Coils

![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/3_ttest.png)</br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/3_ttest_lot1.png)</br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/3_ttest_lot2.png)</br>
![Alt Text](https://github.com/lyanneagger/MechaCar_Statistical_Analysis/blob/main/Resources/3_ttest_lot3.png)</br>

## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?