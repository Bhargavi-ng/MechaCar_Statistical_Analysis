# MechaCar_Statistical_Analysis
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has asked the data analytics team to review the production data for insights that may help the manufacturing team.

The below deliverables need to be provided as part of the study.
- Deliverable 1: Linear Regression to Predict MPG
- Deliverable 2: Summary Statistics on Suspension Coils
- Deliverable 3: T-Test on Suspension Coils
- Deliverable 4: Design a Study Comparing the MechaCar to the Competition

## Deliverable 1: Linear Regression to Predict MPG

### Summary of the linear regression:
A multiple linear regression model was generated using multiple variables from the data source file - [MechaCar_mpg.csv](https://github.com/Bhargavi-ng/bikesharing/blob/main/R_Analysis/MechaCar_mpg.csv). Based on the test results, vehicle length and grond clearance had stastically significant effect on fuel efficiency. They had p-values of 2.60e-12 and 5.21e-8 respectively. As this regression model has an R-squared value of 0.7149, this model can predict approximately 71.5% of the variation in mpg of the MechaCars prototypes. Thus, this model is very effective at predicting the fuel efficiency of the MechaCars. 

MechaCar_mpg
#### Screenshot of the output from the linear regression:
![Deliverable 1 Output](https://github.com/Bhargavi-ng/bikesharing/blob/main/Images/Deliverable1_R_Output.PNG)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  Based on the test results, vehicle_length anf ground_clearance have non-random amounts of variance to the mpg values.

- Is the slope of the linear model considered to be zero? Why or why not?
  The linear model's slope is not considered to be zero as the p-Value for this model is less than the significance level of 0.05.
 
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  This linear model predicts mpg of MechaCar prototypes effectively as the r-squared value is 0.7149, which means that about 71.5% of all mpg predictions will be effectively explained by this model.

  ## Resources:
- R Studio