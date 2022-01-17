# MechaCar_Statistical_Analysis
Module 15.- Rstudio

## Linear Regression to Predict MPG

**Overview of the analysis**

After a while that Jeremy has been promoted, as the Primary Analyst for the company analytic's team, the upper management has contacted him about a special project: review the production data insights that may help manufacturing team and releases their progress.

*Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.*

-Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
For answering this previous question, we had to perform a multiple linear regression, with the follow result:

![Summary_multiple_linear_regression](https://user-images.githubusercontent.com/90433064/149705627-d457a364-6a67-48f2-8c65-00061b5a164d.jpg)

So then, as we can see the values that rovided a non random amount of variance to the mpg values are vehicule weight, spoiler angle and AWD. 

-Is the slope of the linear model considered to be zero? Why or why not?

For this question, we would have the follow hypothesis:
 
![Hypotheses](https://user-images.githubusercontent.com/90433064/149707768-dad29027-7211-4e06-9f0c-a03bb5529ee1.jpg)

![p_value](https://user-images.githubusercontent.com/90433064/149709256-5e24cd03-c254-446f-9f5a-97eb17d83ce5.jpg)

As we can noticed the p-value of our linear regression analysis is 5.35 x 10^-11, so it is smaller than the normal range of significance level of 0.05%; so then there is sufficient evidence to reject our null hypothesis, meaning that the slope of our linear model is not zero. 

-Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
To answer this questions we should look at the r-squared value, which is 0.71 in our multiple linear regression model, meanign that roughly 71% of the variability of our dependent variable is explained using this linear model. Since the Intercept term is statistically significant as well, it may mean that we need to change our independent variables or reevalueate the coefficients and significance. 

So, we could say that even when the multiple linear regression works ok ar predicting our current dataset, fails to generalize and predicting future data correctly. We should consider to change the independent variables or re-evaluate the coefficients and significance.

## Summary Statistics on Suspension Coils

*Write a short summary using screenshots from your total_summary and lot_summary dataframes, and address the following question:*

-The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

This was the result for all manufacturing lots, getting 62.29 pounds PSI which fit the design specification:

![Variance_Suspension_coils](https://user-images.githubusercontent.com/90433064/149716730-24d07b89-320f-4f22-a292-57a1509aab9f.jpg)

Nevertheless, the result was different on the results of each lots individually:

![variance_per_lot](https://user-images.githubusercontent.com/90433064/149717672-97c70d86-16e8-4d5f-ae85-d777c3b3b9e2.jpg)

As we can visualize better on the following image, Lot 1 and 2 met the design requirement, but we cannot say that for the Lot 3, which has a variance of 170 pounds PSI.

![boxplot_variance_per_lot](https://user-images.githubusercontent.com/90433064/149717392-e74fbea8-be7c-4f8b-9b57-2ca4406e7476.jpg)


## T-Tests on Suspension Coils
Briefly summarize your interpretation and findings for the t-test results

## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

In your description, address the following questions:
-What metric or metrics are you going to test?

-What is the null hypothesis or alternative hypothesis?

-What statistical test would you use to test the hypothesis? And why?

-What data is needed to run the statistical test?
