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
...ACTUAL NUMBERS, ACTUAL GROWTH RATES, THE MONTHS AND THE PRODUCTS THAT DO WELL OR BADLY AND  BE MORE SPECIFIC
- The company sales showed a seasonal trend where the sales exhibits a noticable spike in December, December 2010 (288.76M) and December 2011 (288.08M) following normal holiday seasonality patterns, driven by 
  increased consumer spending, while the month of January registered the least sales, January 2011 (163.70M) and January 2012 (168.89M) mostly due to consumers cut back on spending after 
  overspending during the holidays. 
- Beginning in February of 2010 there was an alternating increase and decrease trend of weekly sales with September (177.27m) being the month with the least sales of the year, mostly due to lack of major holidays that 
  drive high consumer spending.
- Among the years there was a significant increase in weekly sales between the year 2010 and 2011 with a YoY of 6.96% and a significant decrease in sales in the year 2012 (-18.3%), this could be attributed to the highest 
  unemployment rate. 
  ![P2](https://github.com/user-attachments/assets/673ae401-48f3-437a-860d-455a6d989fed)



#### Key Store Performance:
- Over the period of these three years store 20 executed the highest average weekly sales (301.40M), this could be attributed to its  easy accessibility like being located near major roads, highways, or public transport 
  hubs, which increases visits.
- Store 33 showed consistent underperformance (37.16M), potentially due to regional economic factors and ineffective promotional strategies that don’t align with customer preferences, or mismatch with local community’s 
  needs and culture.
- 39.05% of the company's sales are from the top 10 best performing stores and bottom 10 worst performing stores contributes only 7.47%, with the rest of the stores contributing 53.48%.   
  ![P3](https://github.com/user-attachments/assets/09ed75dd-5d25-4195-833b-5e91472b00ad)



#### Economic Influences:
- With correlation coefficient being 0, CPI showed no significant impact on sales during holiday and non-holiday periods.
  This suggests that CPI alone does not strongly influence sales trends, the lack of correlation with CPI does not mean CPI has no influence, it might act indirectly or in combination with other variables.
  Other variables in the dataset, like fuel price, unemployment rate, or temperature, may have a stronger impact on sales.
![P4](https://github.com/user-attachments/assets/61b8c492-92fc-4a8d-8956-f9872b38e4bc)



### Recommendations: 
...THEY SHOULD BE TIED TO THE INSIGHTS WEVE FOUND- LIST THE PRODUCTS AND GIVE A REASON WHY SO E.G GIVEN THE UPWARD TREND IN ELECTRIC LETTER OPENERS AND BLANK IN THE TECHNOLOGY  CATEGORY CONSIDER RE-ALLOCATING MARKETTING BUDGET FOR THE NEXT 2 YEARS TO FOCUS ON THESE PRODUCTS....NB: what if asked this in an interview(16:01)..can explain it??

 Based on the uncovered insights, the following are actionable recommendations to improve sales performance, optimize resources, and align strategies with consumer behavior:
 - Introduce mid-week or weekend sales and also launching of aggressive marketing campaigns during non-holidays to capitalize on increased consumer spending.
 - With store 33 being the worst performing stores, there can be an introduction of attractive deals like location-specific promotions or loyalty programs to boost foot traffic and increase customer retention in the 
   bottom 10 underperforming stores.
 - Despite a correlation of zero between CPI and holiday and non-holiday sales a multivariate analysis can be done including all factors (CPI, fuel price, unemployment rate, temperature) as predictors in a regression 
   model to see how they collectively influence sales.
 - Offer online shopping incentives or delivery discounts during extreme weather conditions to compensate for reduced in-store traffic and also invest in improving the online shopping experience (e.g., user-friendly 
   website, mobile app).

   ### Technical Details:
   The technical analysis involved:
   - Excel (Power query and power pivot) : for data extraction, and advanced exploratory data analysis (EDA) via interactive pivot tables and charts.[here]..
   - SQL: For complex querying and analysis of sales and customer data.[here}...
   - 

    ### Caveats and Assumptions:
   ...DATA CLEANING PROCESS AND ANY ASSUMPTIONS YOU MADE ABOUT THE DATA.
   Data Completeness: A significant portion of revenue(15%) came from 'unclassified' categories, which may reflect product categorization inconsistencies or data entry issues.







