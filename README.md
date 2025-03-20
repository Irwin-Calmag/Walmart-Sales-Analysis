## Walmart Sales Analysis
### Project Background
Walmart, an American multinational retail corporation that operates a chain of hypermarkets, discount department stores, and grocery stores in the United States and 23 other countries. It's headquartered in Bentonville, Arkansa.
This project thoroughly analyzes and synthesizes this multifaceted data in order to uncover critical insights that will improve performance across sales, stores, and marketing teams.

Insights and recommendations are provided on the following key areas:

- Sales Trends Analysis: Evaluation of performance differences between holiday and non-holiday weeks and yearly sales trends.4 WHAT?, Y SO?
   - This is useful in the prediction of future sales performance and determination of how promotions, discounts, and seasonal factors impact revenue.
- Store Level Performance: Determine the best-performing and worst-performing stores and also top 10 best and worst performing stores. 4 WHAT?, Y SO?
  -  Ensures top-performing stores get enough stock to meet demand and through benchmarking worst performing stores can boost their profitability by identifying and replicating successful store strategies. 
- Economic Influence: Explore relationships between sales, economic indicators(CPI,unemployment), and external factors(temperature,fuel price)during holiday and non-holiday weeks.4 WHAT?, Y SO?
  - Boosts sales strategies by aligning with economic conditions eg If unemployment is high, retailers might focus on budget-friendly products to attract cost-conscious buyers.



### DATA STRUCTURE OVERVIEW
....The store has significant amount of data on its weekly sales, CPI(consumer price index), unemployment rate, temperature and holidays.
ILL JUST DO AN ERD ONLY
  ERD -- ITS A MUST

### Executive Summary:
#### Overview of findings
Walmart's sales analysis of 6434 records from 2010 to 2012 reveals annual revenue stabilizing at $2.29 billion in 2010, with July (232.58m) and December (288.76m) being the highest performing months, while March (181.92m) recorded the lowest sales.The company experienced a 6.96% year-over-year growth in 2011, but sales saw a significant decline of 18.30% in 2012. While this decline can be broadly attributed to struggling local economy and high unemployment rates that reduces purchasing power, Walmart can benefit from expanding top performing stores, optimizing bundling, and enhancing loyalty programs to increase customer lifetime value. Additionally, with only 7.47% of the company's sales coming from the bottom 10 performing stores, targeted growth along with enablization of dynamic pricing strategies to maximize profits, will strengthen their market position and drive sustainable growth.


Below is the overview page from the powerBI dashboard and more examples are included throughout the report.
![P1](https://github.com/user-attachments/assets/f07ac416-78bd-4790-a2b8-168cb29dbc5e)

### INSIGHTS DEEP DIVE
#### Sales Trends and Growth Rates:
- The company sales showed a seasonal trend where the sales exhibits a noticable spike in December, December 2010 (288.76M) and December 2011 (288.08M) following normal holiday seasonality patterns, driven by 
  increased consumer spending, while the month of January registered the least sales, January 2011 (163.70M) and January 2012 (168.89M) mostly due to consumers cut back on spending after 
  overspending during the holidays. 
- Starting in February 2010, weekly sales followed an alternating pattern of increases and decreases, with September ($177.27M) recording the lowest sales of the year, primarily due to the absence of major holidays that 
  typically drive higher consumer spending.
- Between 2010 and 2011, weekly sales saw a significant increase, with a year-over-year growth of 6.96%, while 2012 experienced a sharp decline of 18.3%. This downturn could be attributed to the high unemployment 
  rate, which impacted consumer spending.
  ![P2](https://github.com/user-attachments/assets/673ae401-48f3-437a-860d-455a6d989fed)



#### Key Store Performance:
- Over the three-year period, Store 20 recorded the highest average weekly sales ($301.40M), likely due to its easy accessibility, such as being located near major roads, highways, or public transport hubs, which drive 
  higher foot traffic.
- Store 33 showed consistent underperformance (37.16M), potentially due to regional economic factors and ineffective promotional strategies that don’t align with customer preferences, or mismatch with local community’s 
  needs and culture.
- The top 10 best-performing stores account for 39.05% of total sales, while the bottom 10 worst-performing stores contribute only 7.47%, with the remaining 53.48% coming from all other stores.
- The unemployment rate during the period ranged from a minimum of 3.879% to a maximum of 14.313%.
  
  ![P3](https://github.com/user-attachments/assets/09ed75dd-5d25-4195-833b-5e91472b00ad)



#### Economic Influences:
- With correlation coefficient being 0, CPI showed no significant impact on sales during holiday and non-holiday periods,
  this suggests that CPI alone does not strongly influence sales trends.
- The lack of correlation with CPI does not mean CPI has no influence, it might act indirectly or in combination with other variables.
  Other variables in the dataset, like fuel price, unemployment rate, or temperature, may have a stronger impact on sales.



### Recommendations: 
Based on the uncovered insights, the following are actionable recommendations to improve sales performance, optimize resources, and align strategies with consumer behavior:
 1. Enhance Customer Engagement
  - Introduce mid-week or weekend sales and also launching of aggressive marketing campaigns during non-holidays to capitalize on increased consumer spending.
  - Offer online shopping incentives or delivery discounts during extreme weather conditions to compensate for reduced in-store traffic and also invest in improving the online shopping experience (e.g., user-friendly 
    website, mobile app).
 2. Strengthen Market Presence
 - With store 33 being the worst performing stores, there can be an introduction of attractive deals like location-specific promotions or loyalty programs to boost foot traffic and increase customer retention in the 
   bottom 10 underperforming stores.
 3. 
 - Despite a correlation of zero between CPI and holiday and non-holiday sales a multivariate analysis can be done including all factors (CPI, fuel price, unemployment rate, temperature) as predictors in a regression 
   model to see how they collectively influence sales.
   

   ### Technical Details:
   The technical analysis involved:
   - Excel (Power query and power pivot) : for data extraction, and advanced exploratory data analysis (EDA) via interactive pivot tables and charts.[here]..
   - SQL: For complex querying and analysis of sales and customer data.[here}...
   - 

    ### Caveats and Assumptions:
   ...DATA CLEANING PROCESS AND ANY ASSUMPTIONS YOU MADE ABOUT THE DATA.
   Data Completeness: A significant portion of revenue(15%) came from 'unclassified' categories, which may reflect product categorization inconsistencies or data entry issues.







