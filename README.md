# Walmart Sales Analysis
# Project Backgroung
Walmart is an American multinational retail corporation that operates a chain of hypermarkets(supermarkets), discount department stores, and grocery stores in the United States and 23 other countries. It is headquartered in Bentonville, Arkansa.
The store has significant amount of data on its weekly sales, CPI(consumer price index), unemployment, temperature and holidays. This project thoroughly analyzes and synthesizes this data in order to uncover critical insights that will improve Walmart's commercial success.
Insights and recommendations are provided on the following key areas:
1. Sales trends: Analyze performance differences between holiday and non-holiday weeks and yearly sales trends.
2. Store performance: Determine the best-performing and worst-performing stores.
3. Economic influence: Explore relationships between sales, economic indicators(CPI,unemployment), and external factors(temperature,fuel price)during holiday and non-holiday weeks.
The excel queries utilized to clean, categorize, and prepare data for the dashboard can be found here.
An interactive power bi dashboard can be downloaded here.
Targeted SQL queries regarding various business questions can be found here.
The SQL queries utilized to inspect and perform quality checks can be found here.

# Data Strucrure & Initial Checks 
Include an ERD (Entity relationship diagram)- can be created using CANVA 
The dataset consists of the following columns:
1.	Store: Unique identifier for each Walmart store.
2.	Date: The week ending date for the recorded sales.
3.	Weekly_Sales: Total sales for the week at a given store.
4.	Holiday_Flag: Binary indicator (1 if the week includes a major holiday, 0 otherwise).
5.	Temperature: Average temperature for the week.
6.	Fuel_Price: Weekly average fuel price in the region.
7.	CPI: Consumer Price Index, reflecting inflation trends.
8.	Unemployment: Unemployment rate in the region.

# Executive Summary:
Overview of findings
After peaking in 2010 (2.29bn), the company sales have continued to peak with significant increase in 2011 (2.45bn), but there is a significant drop in 2012 (2.00bn). Key performance indicators have all shown the year-over-year sales changes. While this decline can be broadly attributed to struggling local economy or high unemployment rates that reduces purchasing power, the following section will explore additional contributing factors and highlight key opportunity areas for improvement.
Below is the overview page from the powerBI dashboard and more examples are included throughout the report. The entire interactive dashboard can be downloaded here.
(Screenshot of dashboard)

Sales Trends:
Holiday impact- Sales fluctuate significantly across weeks, with noticeable spikes during holiday periods, among holidays, Christmas and Thanksgiving have the highest positive impact, driven by increased consumer spending on these specific holidays, while others show moderate effects.
Beginning in February of 2010 there was an alternating increase and decrease trend of weekly sales with September (177.3m) being the month with the least sales of the year.
Among the years there was a significant increase in weekly sales between the year 2010 and 2011 with a YoY of 6.96% and a significant decrease in sales in the year 2012 (-18.3%), this could be attributed to the highest unemployment rate. 
(Screenshot-table of sales)

Store Performance:
Over the period of these three years store 20 executed the highest average weekly sales, this could be attributed to their easy accessibility like being located near major roads, highways, or public transport hubs, which increases visits.
While Store 33 showed consistent underperformance, potentially due to regional economic factors and ineffective promotional strategies that don’t align with customer preferences, or mismatch with local community’s needs and culture.
(Screenshot-table of sales of store performance)

Economic Influences:
-CPI showed no significant impact on sales during holiday weeks and non-holiday periods.
This suggests that CPI alone does not strongly influence sales trends, the lack of correlation with CPI does not mean CPI has no influence, it might act indirectly or in combination with other variables.
Other variables in the dataset, like fuel price, unemployment rate, or temperature, may have a stronger impact on sales.
(Screenshot-table of sales of temperature and sales)

# Recommendations: 
Abt 5 key points- [WHY DOES IT MATTER THAT YOU LOOKED AT WHAT YOU LOOKED AT]-9:57
Based on the uncovered insights, the following are actionable recommendations to improve sales performance, optimize resources, and align strategies with consumer behavior:
•	Introduce mid-week or weekend sales and also launch aggressive marketing campaigns during non-holidays to capitalize on increased consumer spending.
•	With store 33 being the worst performing stores, there can be an introduction of attractive deals like location-specific promotions or loyalty programs to boost foot traffic and increase customer retention in the bottom 10 underperforming stores.
•	Despite a correlation of zero between CPI and holiday and non-holiday sales a multivariate analysis can be sone including all factors (CPI, fuel price, unemployment rate, temperature) as predictors in a regression model to see how they collectively influence sales.
•	Offer online shopping incentives or delivery discounts during extreme weather conditions to compensate for reduced in-store traffic and also invest in improving the online shopping experience (e.g., user-friendly website, mobile app).







