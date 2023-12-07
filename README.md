# Linear-Regression-on-marketing-and-sales-data
## Overview
This repository contains 3 codes:
### 1. Simple Linear Regression
The project focuses on the use of influencer marketing, and exploring the relationship between marketing promotional budgets and sales. The dataset provided includes information about marketing campaigns across TV, radio, and social media, as well as how much revenue in sales was generated from these campaigns. TV was found to be the most influential promoter of sales.
### 2. Multiple linear regression
Each row corresponds to an independent marketing promotion where their business uses TV, social media, radio, and influencer promotions to increase sales. Expand analysis to include other variables that can help  target the marketing efforts
### 3. ANOVA testing
Use the data to run a one-way ANOVA and a post hoc ANOVA test to know if sales are significantly different among various TV and influencer promotion types.

## Business Understanding
Based on these analyses, decisions can be made about where to focus future marketing efforts.

## Data Understanding
This activity uses a dataset called marketing_sales_data.csv. It represents the amount of money spent on TV, radio, and social media promotions, as well as the corresponding sales. It is a fictional dataset that was created for learning purposes and made available on Kaggle. The data has been modified for this activity. 

## Modeling and Evaluation
### 1. Simple Linear Regression
According to the model, when TV is used as the independent variable X, an increase of one million dollars for the TV promotional budget results in an estimated 3.5614 million dollars more in sales.

### 2. Multiple Linear Regression
According to the model, high TV promotional budgets result in significantly more sales than medium and low TV promotional budgets. For example, the model predicts that a Low TV promotion is 154.2971 lower on average than a high TV promotion given the same Radio promotion. The coefficient for radio is positive, confirming the positive linear relationship shown earlier during the exploratory data analysis.

### 3. ANOVA
One-way ANOVA can be used to determine if there are significant differences among the means of three or more groups. ANOVA post hoc tests provide a more detailed view of the pairwise differences between groups.
The results of the one-way ANOVA test indicate that the null hypothesis that there is no difference in Sales based on the TV promotion budget can be rejected. Through the ANOVA post hoc test, a significant difference between all pairs of TV promotions was found. The difference in the distribution of sales across TV promotions was determined significant by both a one-way ANOVA test and a Tukey’s HSD test

## Conclusion
Thus, it is recommended that the business allot a high promotional budget to TV when possible and invest in radio promotions to increase sales.

