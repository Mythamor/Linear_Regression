## Simple Linear Regression

> ### 1. Simulate a dataset of 100 rows with the following:

1. X1: Normally distributed, mean = 50, SD = 25
2. X2: Normally distributed, mean = 10, SD = 2
3. X3: Binary variable (0 or 1), with a 30% probability of being 1
   
(Tip: Use a Bernoulli distribution with p = 0.3 — the exact proportion in your dataset may vary slightly.) 

> ### 2. Generate the outcome variable y as:

Create y using the formula:

y = 1 * X1 + 5 * X2 + 10 * X3 + error

Where: error is a random value drawn from a normal distribution with a mean of 0 and a standard deviation of 2.

> ### 3. Fit a linear regression model:

Model: y ~ X1 + X2 + X3
Use the statsmodels library in Python.

>## Output the following:
1. Coefficients for each variable
2. R-squared value
3. P-values for each coefficient
