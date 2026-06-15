# Facebook Ads Campaign Performance Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)

## Description

Analysed Facebook Ads campaign data to evaluate spend efficiency, ROMI trends, and the relationships between key advertising metrics. The analysis covers daily spend patterns, campaign-level performance comparison, and correlation analysis to identify what drives campaign profitability.

![Rolling Spend](images/rolling_spend.png)

## My Tasks

- Analysed daily ad spend trends for 2021, including 7-day rolling averages to smooth out daily fluctuations
- Calculated daily and rolling ROMI (Return on Marketing Investment) to track campaign efficiency over time
- Compared total spend and ROMI across campaigns using bar charts and box plots to identify performance variation and consistency
- Built a correlation heatmap across spend, impressions, clicks, value, CPC, CPM, CTR, and ROMI to identify key performance drivers
- Visualised the relationship between spend and total value using a regression plot

![Correlation Heatmap](images/heatmap.png)

## Result

Total value showed the strongest correlation with total spend, while ROMI showed weak correlation with spend and other metrics — meaning higher spend doesn't reliably predict higher returns. Campaign-level comparison revealed significant ROMI variation, highlighting which campaigns were efficient versus which were driving unnecessary spend without proportional returns.

![ROMI by Campaign](images/romi_by_campaign.png)
