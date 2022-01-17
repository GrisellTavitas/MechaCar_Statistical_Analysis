# MechaCar_Statistical_Analysis
Module 15.- Rstudio

## Linear Regression to Predict MPG

**Overview of the analysis**

After a while that Jeremy has been promoted, as the Primary Analyst for the company analytic's team, the upper management has contacted him about a special project: review the production data insights that may help manufacturing team and releases their progress.

*Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.*

-Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
For answering this previous question, we had to perform a multiple linear regression, with the follow result:

![Summary_multiple_linear_regression](https://user-images.githubusercontent.com/90433064/149705627-d457a364-6a67-48f2-8c65-00061b5a164d.jpg)

So then, as we can see the values that could predict the mpg of MechaCar prototypes are vehicule weight, spoiler angle and AWD; because they are statistically provided a non random amount of variance to the mpg values. 

-Is the slope of the linear model considered to be zero? Why or why not?

For this question, we would have the follow hypothesis:
 
![Hypotheses](https://user-images.githubusercontent.com/90433064/149707768-dad29027-7211-4e06-9f0c-a03bb5529ee1.jpg)

![p_value](https://user-images.githubusercontent.com/90433064/149709256-5e24cd03-c254-446f-9f5a-97eb17d83ce5.jpg)

As we can noticed the p-value of our linear regression analysis is 5.35 x 10^-11, so it is smaller than the normal range of significance level of 0.05%; so then there is sufficient evidence to reject our null hypothesis, meaning that the slope of our linear model is not zero. 

-Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?


## Study Design: MechaCar vs Competition


Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

In your description, address the following questions:
-What metric or metrics are you going to test?

-What is the null hypothesis or alternative hypothesis?

-What statistical test would you use to test the hypothesis? And why?

-What data is needed to run the statistical test?
