# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

   The main objective behind analysis in to find out how NYC bike sharing business work? for this we used 201908-citibike-tripdata and perfoming analysis based on tableau chart to give answer to differnt questions regarding NYC bike sharing.
   
![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/8731fb2b476084975eec52b4f6b1261221f1098d/Image/1.png)
 
Output of multiple linear regression using the lm() function produces the coefficients for each variable in the linear equation.above image shows the coefficient for vehicle_weight,spoiler_angle,ground_clearence,AWD and MPG. using coefficicents we can write our linear model as per follow:
 
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

![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/43752515560145a413c4041f8b660ec26db2f500/Image/4.png)

![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/43752515560145a413c4041f8b660ec26db2f500/Image/lot2.png)

![image](https://github.com/sanjal7137/MechaCar_Statistical_Analysis/blob/43752515560145a413c4041f8b660ec26db2f500/Image/lot3.png)



 
## Results



Using differnt parameters(field) in NYC city bike sharing data like starttime,endtime,gender etc. find out following results:-

### 1. checkout times for users:-

   Following image shows Checkout times for users for every hours in day means it shows tripduration for particular minute and  particular hour. For example 104824 rides checkout by Male 34151 rides checkout by Female and 6172 rides checkout by Unknown for Hour of tripduration: 0 and Minute of tripduration:6 .



### 2. checkout times by gender :-

   Following image shows Checkout times for users by gender for every hours in day means it shows tripduration for particular minute and  particular hour gender wise. For example 375 rides for Hour of tripduration: 1 and Minute of tripduration:19 .


![image](https://github.com/sanjal7137/bikesharing/blob/30e19fbb221e77b55120205d01abb6d767caf894/Images/2new.png)

### 3. Trips by weekday for each hour :-

   Following image shows Number of bike trips by weekday for each hour of the day means it shows tripduration for particular hour and  particular weeday. For example 43982 rides for Hour of staettime: 5 PM and Weekday of stoptime is Thursday.
