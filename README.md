# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
![linear_regression](Resources/linear_regress.PNG)
*From the summary, we can see that, vehicle weight and spoiler angle have nearly no impact on the mpg of the vehicle.
<br />*The p-value of this regression model is 5.35e-11 which is much smaller than our assumed significance level. Therefore, we can reject null hypothesis, state that the two means are statistically different. 
<br />*The slope are not zero for vehicle_length, AWD and ground_clearance.

## Summary Statistics on Suspension Coils
![total_summary](Resources/total_summary.PNG)
![lot_summary](Resources/lot_summary.PNG)
<br />In total, the current manufacturing data meets the design specification. However, the data of lot 3 alone does not. The variance of this lot is 220.01, which is higher than the requirements of 100.

## T-Tests on Suspension Coils
![t_test](Resources/t_test.PNG)
<br />H0: there is no statistical difference
<br />Ha: there is statistical difference
<br />population mean: 1500 lbs per square inch
 
 ## Study Design: MechaCar vs Competition
 If the price we planned to sell our vihecles are the same as our competitors, we would need to look into how we surpass our competitors in other fields, such as fuel efficiency.
 We will need to consider factors like distances and weather conditions and compare the dataset with comparable vahicles from competitors.
 <br />We will need to set up a paired t-test.
 <br />H0: the difference between our paired observations is equal to zero (no statistical difference)
 <br />Ha: the difference between our paired observations is not equal to zero 
 <br />Parameters include:
 <br />`x: our mpg dataset as vector of numbers`
 <br />`y: competitors mpg dataset as vector of numbers`
 <br />paired: `must be set to TRUE`
 <br />alternative: `tells the function if the hypothesis is one-sided or two-sided`
 
 
 
