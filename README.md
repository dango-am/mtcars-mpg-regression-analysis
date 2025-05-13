MTCARS miles per galon(MPG) Regression Analysis

This project performs a multiple linear regression analysis on the `mtcars` dataset to predict miles per gallon (mpg), which represents fuel efficiency. The goal is to explore the mtcars data set to determine differnt car features effect in miles per gallon of a car and to evaluate the assumptions of linear regression to ensure the reliability of the model.

Dataset used

This analysis was mad by using the mt cars dataset, which contains data on fuel consumption and 10 aspects of automobile design and performance for 32 cars (1973–74 models).

Features Used

The following independent variables were selected to predict `mpg`:
- `hp`: Gross horsepower
- `wt`: Weight (1000 lbs)
- `qsec`: 1/4 mile time
- `cyl`: Number of cylinders
- `disp`: Displacement (cu.in.)

Objectives

1. Fit a multiple linear regression model with `mpg` as the dependent variable.
2. Check for the core assumptions of linear regression:
   - Linearity
   - Homoscedasticity (constant variance of residuals)
   - Normality of residuals
   - Multicollinearity
3. Apply remedial measures if assumptions are violated.
4. Refit the model and interpret the final results.

Methodology

- Model fitting and diagnostics were conducted using R.
- Differnt visual and statistical tests were used to assess assumptions.
- Model was adjusted accordingly based on diagnostic outcomes.

Results & Conclusion

- The final model shows how engine and performance characteristics influence mpg.
- Interpretation and discussion are included based on the adjusted model's performance.


