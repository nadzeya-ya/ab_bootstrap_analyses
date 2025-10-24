A/B Test Analysis Breakdown
1. Data Preparation
Loaded user data (revenue and group A/B), checked for uniqueness, completeness, and balanced group sizes — ensuring data quality and reliable analysis.
2. Exploratory Analysis and Visualization
Examined spending distributions and plotted histograms to understand data patterns and choose appropriate comparison methods.
3. Comparing Average Revenue (ARPU)
Calculated average revenue per user (ARPU) for both groups. Tested whether the difference was statistically significant using hypothesis tests and bootstrapping.
4. Conversion Rate Analysis
Identified the share of paying users in each group and compared them using a chi-squared test.
5. Revenue Difference Testing
Since revenue data were not normally distributed, applied the Mann–Whitney test to compare group medians.
6. Bootstrapping Mean Differences
Simulated multiple “virtual” experiments to assess whether the observed difference could have occurred by chance.
7. Summary
Combined all results: the new promo slightly increased conversion, but the difference in average revenue was not statistically significant. Recommendation — continue testing before scaling.
