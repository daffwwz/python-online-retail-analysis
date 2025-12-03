# Online Retail Analysis

## Tools Used
**Python**:
1. Pandas: a powerful Python library used for data analysis and manipulation, such as cleaning datasets, aggregating data, and performing statistical calculations.
2. Matplotlib: a Python library for creating visualizations, including line plots, bar charts, histograms, and more, to help interpret data.
3. Data Wrangler (VS Code Extension): a VS Code extension that provides pre-built code snippets and interactive tools to speed up data analysis workflows in Python, especially when working with Pandas and Matplotlib.
## Dataset Source
**UCL Machine Learning Repository**: [Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

This is a transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## What I've Learned So Far
1.  Common data exploration: count missing values, drop the missing values that comes from `CustomerID` because they are invalid data, clean duplicates from Invoice Number so that each Invoice Number is unique (this still need to be verified by the author), get the data statistics summary.
2.  Visualize some plots related to Business Performance & Revenue Analysis

## Visualization using Matplotlib
### Top 10 Countries by Transactions
![Top 10 Countries by Transactions](./images/top_10_countries_transactions_labeled.png)
**Insights:**
1. **Market segmentation by country:** The chart allows us to see which countries contribute the largest share of transactions, enabling targeted marketing or resource allocation.
2. **Customer base distribution:** Countries with higher transaction counts indicate a more active or larger customer base, which can guide expansion or retention strategies.
3. **Opportunity identification:** Countries outside the top 10 may represent untapped markets or regions with growth potential.
4. **Strategic planning:** Understanding transaction distribution can inform inventory management, logistics planning, and promotional campaigns tailored to high-performing countries.

**Conclusion:**
This visualization is an essential tool for geographic market analysis, helping the business prioritize efforts, identify key markets, and optimize sales strategies based on country-level performance.

### Top 10 Customers by Transactions
![Top 10 Customers by Transactions](./images/top_10_customers_transactions.png)
**Insights:**
1. **Customer prioritization:** Focus customer service efforts on high-value or frequent buyers to strengthen loyalty.
2. **Targeted promotions:** Offer personalized discounts, gifts, or exclusive offers to top customers to encourage repeat purchases (can be used for lists top 15% customers to create personalized discount).
3. **Loyalty programs:** Design reward programs based on transaction frequency or value, ensuring the most engaged customers are recognized.
4. **Behavior understanding:** Study the purchasing patterns of top customers to inform product recommendations or marketing strategies.
5. **Retention strategies:** Identify top customers at risk of churn and proactively engage them (can be used for personalized time-series customers buying frequency).

**Conclusion:**
Analyzing the top customers by transactions provides actionable insights for enhancing customer experience, increasing retention, and maximizing revenue from the most valuable segment of your customer base.

### Top 10 Products by Revenues
![Top 10 Products by Revenues](./images/top_10_products_revenue.png)
**Insights:**
1. **Product prioritization:** Focus inventory management, marketing, and sales efforts on high-revenue products.
2. **Promotional planning:** Design discounts or bundles around top-performing products to boost overall sales.
3. **Product lifecycle management:** Monitor revenue trends for these products to anticipate demand, plan restocking, or consider product updates.
4. **Strategic decision-making:** Inform product development and expansion strategies based on what drives the most revenue.

**Conclusion:**
Analyzing the top products by revenue provides actionable insights for sales strategy, inventory planning, and revenue growth, ensuring the business invests resources where they have the most impact.

### Total Revenues in 2011
![Total Revenues in 2011](./images/yearly_total_revenue_2011.png)
**Insights:**
1. **Monthly or quarterly trends:** Determine which months generated the highest revenue (ex: holiday seasons or special events).
2. **Off-peak strategies:** Identify months with lower revenue and design promotions or campaigns to boost sales during these periods.
3. **Forecasting:** Use seasonal patterns to predict future monthly revenue and improve cash flow management.
4. **Performance evaluation:** Compare actual revenue to seasonal expectations to assess the effectiveness of sales and marketing strategies.

**Conclusion:**
Analyzing revenue seasonality allows the business to align operational, marketing, and financial strategies with customer purchasing behavior, maximizing revenue and efficiency throughout the year.
