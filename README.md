# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Vehichle_length and Ground_clearance are the ones that provide a non-random amount of variance.

Is the slope of the linear model considered to be zero? Why or why not?
No, because there is an increment in the slope from the Vehichle_length and Ground_clearance.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Partially for the slight correlation from the Vehichle_length and Ground_clearance that the slope provides.

![values](https://github.com/LennethNova/MechaCar_Statistical_Analysis/blob/main/images/01.PNG)

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
The variance across all the lots does not exceed the 100 pound per square inch variance, although when analyzing the individual lots, Lot 3 presents a higher variance than the expected 100 PSI with a total of 170.29.

![combined](https://github.com/LennethNova/MechaCar_Statistical_Analysis/blob/main/images/02.PNG)

![lots](https://github.com/LennethNova/MechaCar_Statistical_Analysis/blob/main/images/03.PNG)

## T-Tests on Suspension Coils

Only when measuring the Lot 3 mean PSI difference to the 1500 population standard, provided a lower mean value. Statistical significance difference was observed, therefore accepting Ha.

Non other comparison resulted in such findings.

![ttest](https://github.com/LennethNova/MechaCar_Statistical_Analysis/blob/main/images/04.PNG)

![ttest-lots](https://github.com/LennethNova/MechaCar_Statistical_Analysis/blob/main/images/05.PNG)

# Design Study

- What metric or metrics are you going to test?
Metrics: cost, fuel efficiency (city and highway), maintenance cost and safety ratings.

- What is the null hypothesis or alternative hypothesis?
*Null hypothesis:* There is no mean difference among the metrics of cars form MechaCar and the competition.
*Alternative hypothesis:* there is mean difference among the metrics of cars form MechaCar and the competition.

- What statistical test would you use to test the hypothesis? And why?
t.test to compare each metric, for it provides conclusive evidence of the mean differences among the metrics.

- What data is needed to run the statistical test?
At least fifteen random samples for each metric from each competitor to determine if there is statistical mean difference.
