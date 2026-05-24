# Multiple Linear Regression: Multi-Channel Marketing Analysis

## Project Overview
This project applies Multiple Linear Regression to a multi-channel marketing dataset. The goal is to isolate the individual impact of TV, Radio, and Social Media advertising on overall Sales, allowing for a highly optimized budget allocation strategy. 

Unlike simple regression, this analysis accounts for the simultaneous effects of multiple channels and addresses statistical challenges like multicollinearity.

## Environment Setup
Ensure you have Python installed, then install the required libraries:
`pip install pandas numpy matplotlib seaborn statsmodels scipy`

## Key Business Insights
* **Dominant Driver:** TV remains the strongest driver of sales volume. Holding Radio and Social Media constant, every $1,000 increase in TV ad spend yields a significant increase in Sales.
* **Secondary Channel:** Radio also provides a statistically significant, independent contribution to sales.
* **Inefficient Spend:** Social Media ad spend did not show a statistically significant impact on sales (p-value > 0.05).
* **Recommendation:** Reallocate the budget away from Social Media and distribute it between TV (primary) and Radio (secondary) to maximize overall ROI.
