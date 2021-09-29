# Blue Cars Analysis and Hypothesis Testing
The main objective of this project is to investigate a claim about the blue cars for the Autolib electric car-sharing service company
Below is the dataset used for this project
https://colab.research.google.com/drive/1p9jZMkie111EP5lpvwPmbGX2gTzJBrIV?usp=sharing

# Tools Used
Python Notebook, Jupiter Notebook

# Requirements
Programming skills with Python and Jupiter Notebook

# Other tools
Google Docs to draft a report of the hypothesis test 

# Analysis
In this phase we conduct Univariate analysis and Bivariate analysis on the given dataset
In Univariate analysis we analyze one variable at a time whereas in Bivariate analysis we analyze two variable at the same time

# Hypothesis Testing

The hypothesis test we will perform is to investigate the claim that that
the number of blue cars in postal code 95880  is greater than in postal code 91330

## Null Hypothesis
The null hypothesis in this test is that:
The  average number of Bluecars taken in postal code 95880  is greater than in postal code 91330

## Alternative Hypothesis
The alternative hypothesis in this test is that:
The  average number of Bluecars taken in postal code 95880  is not greater than in postal code 91330

## Level of Significance
We will test the results against 0.05 level of significance

## Test statistic
The test statistic we will use will depend on the sample size chosen and also the normality of the distribution
That is, if you are testing a hypothesis about a mean, you have what appears to be normal data, 
and you have a small n(n<30) then you would use a T-test
else we will perform a Z-test

## P-Value

After calculating the test statistic, we determine the P-value 

## Comparing P-Value against the level of significance

We then compare the P-value gotten from the step above with the level of significance.
If the P-value is less than the level of significance,
we reject the null hypothesis
else, if the P-value is greater than the level of significance,
we fail to reject the null hypothesis

## Conclusion

The conclusion will be drawn from the results. That is,
If the P-value is less than the level of significance,
We conclude that null hypothesis is less significant in our hypothesis testing
, and 
If the P-value is greater than the level of significance,
We conclude that null hypothesis is more significant in our hypothesis testing

# Further computations
Determining the Point estimate for the parameter
Calculating the power of test
Discussing Test Sensitivity, that is, how alterance(increase/decrease) of the sample size will affect the power of test
