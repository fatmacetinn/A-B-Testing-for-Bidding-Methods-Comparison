# A/B Testing for Bidding Methods Comparison
Project Overview
This project aims to analyze an A/B test to understand whether the new "average bidding" method introduced by Facebook is more effective in terms of conversions compared to the existing "maximum bidding" method. Our client, bombabomba.com, has conducted this A/B test for a duration of one month and is interested in determining which bidding method yields a higher number of purchases.
Key Metric
The primary success metric for this analysis is the number of purchases (Purchase). Therefore, statistical tests focus on comparing the Purchase metric between the control and test groups.
Data Set
The dataset contains website information from a company, detailing user interactions such as the number of ads seen and clicked, along with the earnings from these actions. There are two distinct datasets representing the control and test groups, provided in an Excel file ab_testing.xlsx with separate sheets for each group.
Variables in the Dataset
•	Impression: Number of ad impressions
•	Click: Number of clicks on the displayed ads
•	Purchase: Number of products purchased after clicking the ads
•	Earning: Earnings from the purchased products
Data Preparation and Analysis
•	Data from both control and test groups are loaded from ab_testing.xlsx.
•	Preliminary data checks and exploration are conducted to understand the dataset's structure, types, and basic statistics.
•	The control group is subjected to Maximum Bidding, and the test group is subjected to Average Bidding.
•	Data from both groups are combined for comparative analysis.
A/B Test Hypothesis
•	Null Hypothesis (H0): There is no difference in the purchase averages between the control and test groups (M1 = M2).
•	Alternative Hypothesis (H1): There is a difference in the purchase averages between the control and test groups (M1 != M2).
Statistical Analysis
•	Shapiro-Wilk test is used to check the normality assumption for the Purchase variable in both control and test groups.
•	Levene’s test is used to assess the homogeneity of variances between the groups.
•	An Independent Samples t-Test (parametric test) is conducted based on the results of the assumption tests.
Results and Conclusions
•	The analysis of the control and test groups' purchase averages is performed, and the t-test is applied to evaluate if there is a statistically significant difference in these averages.
•	Based on the p-value obtained from the t-test, conclusions are drawn regarding the effectiveness of the average bidding method compared to maximum bidding.


![image](https://github.com/fatmacetinn/AB_Testing/assets/142151744/aa5ea16f-fe14-43bb-a3a1-2cea9a64af86)
