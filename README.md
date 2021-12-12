# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

Output of multiple linear regression using the lm() function produces the coefficients for each variable in the linear equation.

![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/8731fb2b476084975eec52b4f6b1261221f1098d/Image/1.png)
 
above image shows the coefficient for vehicle_weight,spoiler_angle,ground_clearence,AWD and MPG. using coefficicents we can write our linear model as per follow:
 
            vehicle_length= -0.00017vehicle_weight - 0.009spoiler_angle - 0.46ground_clearance + 0.40AWD + 0.10 mpg
            
Following image shows statistical metrics using summary function.here p-value for each variable shows significant contribution in linear mlodel.here we can say that ground_clearence and mpg have a significant impact on vehicle length.
            
      
            
  ![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/2a23a6254ddcd8f1dbd85bb3db466c968412cd05/Image/2.png)
  
 ## Summary Statastics for Suspension Coils
 
 The below image shows the total_summary for suspension coils's PSI variable across all lots. here varience is 62.29 that satisfy manufacturing requirements that varience of suspension coils must not exceed 100 pouns per square inch .
 
 ![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/2a23a6254ddcd8f1dbd85bb3db466c968412cd05/Image/5.png)
 
 Below image shows the lot_summary for suspension coils's PSI variable across each lot. from summary we can say that varience for "Lot3" is more than 100 which is not fulfill the manufacturing requirements.
 
 ![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/2a23a6254ddcd8f1dbd85bb3db466c968412cd05/Image/6.png)
 
  ## T-Tests on Suspension Coils
 Below image shows the t-test fuction that determine PSI across all manufacturing lots is statistically different from the population mean of 1,500 pounds per square inch or not? from result of t-test we concentrate on p-value here our p-value is 0.06 is above our significant level therefor we donot have sufficient evidence to reject null hypothesis and we would stat that true mean is not equal to 1500.
 
![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/43752515560145a413c4041f8b660ec26db2f500/Image/3.png)

same as above following three images shows t-test for each manufacturing lot to comare that it statically different from the population mean of 1500 pounds per square inch.

T-test for manufacturing Lot 1

![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/43752515560145a413c4041f8b660ec26db2f500/Image/4.png)

T-test for manufacturing Lot 2

![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/43752515560145a413c4041f8b660ec26db2f500/Image/lot2.png)

T-test for manufacturing Lot 3

![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/43752515560145a413c4041f8b660ec26db2f500/Image/lot3.png)

## Study Design: MechaCar vs Competition

1.To design a statistical study to compare performance of the MechaCar vehicles against performance of vehicles from other manufacturers we follows belows steps.

2.our first step in design statistical study is identify the statistical test here we use two-sample T-test. using p-value in two-sample T-test find significant impact of particular variale on statistical model for both dataset MechaCar and other manufacturer. in our statistical study we can use use different variables like horse_power, mpg, PSI, Fuel_efficiency etc and its mean value.

3.Next step in our study is identifying varible's data types. it is important to identify which varible is numeric and which one is categorical because we need numerical variale for statistical summary like mean,varience,SD etc.

4.Now  its time to build null and alternatiuve hypothesis for example null hypothesis is  MPG  is statistically different from the horse_power mean of 74.

5.Now apply the two-sample statistical test on data to find the p-value.

6.Based on the p-value and significat level we conclude that we can reject null hypothesis or failed to reject null hypothesis. if p-value less than significant level 0.05 than we can say that we can reject null hypothesis otherwise we failde to reject null hypothesis.


