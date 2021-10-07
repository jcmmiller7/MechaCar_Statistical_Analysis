# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="525" alt="Screen Shot 2021-10-07 at 4 56 49 PM" src="https://user-images.githubusercontent.com/85506567/136461051-560e6ec1-0a0b-44d1-b308-cac708666bcc.png">


### The image indicates that the vehicle length and vehicle ground clearance are the most statistically signicant in terms of resulting mpp. This means they provide a non-random amount of variance compared to the other vehicles within the model.

## The P-value for the mdoel is extremely small indicating that there is sufficient evidence to reject the null hypothesis. Thus, the slope of the model is not zero meaning there is some predictive capability. 

##Yes, the model has an r square value of 71% indicating that 71% of the variation in mpg can be explained by the variation of the explanatory variables. Thus, the model is pretty effective. 

## Summary Statistics on Suspension Coils
<img width="491" alt="Screen Shot 2021-10-07 at 5 32 11 PM" src="https://user-images.githubusercontent.com/85506567/136465204-dfc4478e-9087-4018-8112-2cb450f76e03.png">

<img width="644" alt="Screen Shot 2021-10-07 at 5 31 49 PM" src="https://user-images.githubusercontent.com/85506567/136465164-6052e41e-0c87-434a-9818-a3ad7f710faa.png">

### When looking at the average variance in PSI amongst all three lots it is clear that the design specifications are met, however, when you look at the individual lot summaries, there is a great deal of variance within lot 3 is 170 which is significantly greater than the other lots. This may mean there are some issues within the plant that causes this outlier. 

## T-Tests on Suspension Coils

<img width="432" alt="Screen Shot 2021-10-07 at 5 59 02 PM" src="https://user-images.githubusercontent.com/85506567/136467897-ee7c8423-3748-4d40-8a2c-8b449c0e425d.png">

<img width="587" alt="Screen Shot 2021-10-07 at 5 58 31 PM" src="https://user-images.githubusercontent.com/85506567/136467841-93047bd8-a360-4b0e-9311-7c63e6d5b633.png">

### The p value of .06, which is above the .05 threshold, we would not reject (accept) the null hypothesis indicating there is no statistical difference between the sample means and the population means. They means are all relatively similar. We see this same trend within the individual lots as well.  

## Study Design: MechaCar vs Competition.

### One study we could design would be to test the resale value. A few metrics we could test are accidents (binary/categorical vairable), mileage (quantitative), trim package (categorical), engine  type (categorical), maintenace costs (quantitative).

### Null: MechaCar resale value is priced correctly based on the input values.
### Alternate: MechaCar resale value is not priced correclty given the inputs (either under or overvalued)

### We would need probably five years of resale data in order to conduct this study.

### A multiple linear regression would be a good test to run. We could look at the r square value to determine if there is any sort of significant relationship between the input variables and the resale price. We could also run some individual t-tests to determine if certain factors are more statistically significant. 
