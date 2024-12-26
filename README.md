# maven_market_powerbi
# About The Project
Maven Market is a multinational grocery chain operating 24 stores across three countries: 13 in the USA, 9 in Mexico, and 2 in Canada. This project delivers an in-depth analysis of sales, customer behavior, and store performance for a multinational grocery chain operating 24 stores across the USA (13), Mexico (9), and Canada (2). This project focuses on analyzing data from 1998 to uncover key insights into financial performance, customer behavior, and store operations across regions. The interactive dashboard provides actionable insights to support data-driven decision-making, offering a detailed view of sales trends, customer preferences, and store performance across all regions.

# Data Cleaning
I applied ETL (Extract, Transform, Load) processes, utilizing tools like Power BI to efficiently clean, transform, and load the data. This preparation ensured the dataset was ready for analysis and visualization, allowing for smooth, accurate insights into Maven Market’s 1998 sales performance across multiple regions. The data cleaning process included the following steps:

* Header Promotion: Ensured that the first row of data is used as the header for better clarity.
* Data Type Formatting: Adjusted data types to ensure accurate analysis and compatibility with Power BI.
* Calculated Columns: Added new calculated fields to facilitate deeper insights.
* Null Value Replacement: Addressed missing data by replacing null values appropriately.
* Column Merging and Extraction: Combined and extracted relevant columns to streamline the dataset.
* Folder Data Import: Employed the "Folder" option to append multiple related datasets efficiently.
* Data Trimming: Removed unnecessary whitespace from the dataset for cleaner data presentation.
* Standardization: Standardized column names, date formats, and currency to maintain consistency throughout the dataset.
* Data Profiling: Conducted data profiling to ensure quality assurance and identify any data anomalies on the entire dataset.
* Removal of Unwanted Columns and Duplicates: Cleared out irrelevant columns and eliminated duplicate entries to refine the dataset.

# The Data Model
![Screenshot 2024-12-26 193554](https://github.com/user-attachments/assets/ec990639-82ae-4e48-b443-3a5caf82b740)

I established a downward flow data model to ensure a seamless connection between the fact tables and dimension tables. For this model, I employed a Star Schema for all tables, while a Snowflake Schema was utilized for the Stores and Regions tables. The relationships between the tables were established based on the primary and foreign keys, adopting a one-to-many cardinality with a single cross-filter direction. Additionally, I designated the primary key in each table as the key column and hid all foreign keys to streamline the model and enhance clarity.

# Insights
## Topline Performance
![Screenshot 2024-12-26 191555](https://github.com/user-attachments/assets/a42dff37-f613-43dd-81cc-654d6ffd7a63)

The Key Performance Indicators (KPIs) for the current month reveal a 5.60% increase in sales and a 5.61% rise in profit compared to the previous month. Total current month sales amounted to $120,161, with a profit of $71,682 generated from 18,325 transactions. Notably, sales exceeded the monthly target of $119,500. However, product returns were 2.90% higher than the previous month, highlighting potential concerns with customer satisfaction or product quality.

Among the three countries, Mexico emerged as the top performer for the current month, with a 30% increase in sales, profit, and transaction KPIs. A store in Guadalajara, Mexico excelled with over a 65% improvement in monthly performance and a zero return rate. Conversely, a Store in Vancouver, Canada, struggled to meet monthly targets, except in return KPIs, where it showed a reduction in return rates.

## Customer Behavior
![Screenshot 2024-12-26 191501](https://github.com/user-attachments/assets/b244a721-126f-4930-a6b2-8467d6f891b7)
The analysis identified an inverse relationship between income levels and total sales contributions. Customers earning between $10,000 and $50,000, a lower income bracket contributed significantly to the Maven Market's revenue, while higher-income earners, despite their purchasing power, accounted for the smallest share of sales. Educational background also emerged as a critical factor influencing purchasing behavior. The top contributors were customers with high school degrees, bachelor’s degrees, and partial high school education. This data underscores that Maven Market's core audience comprises individuals from accessible education brackets, suggesting that its pricing and product range resonate more with customers prioritizing affordability and familiarity.

These insights provide a valuable perspective on customer behavior, revealing opportunities to tailor marketing strategies and refine product offerings. By leveraging this data, Maven Market can align its promotional activities and inventory with the needs and preferences of these key segments, further solidifying its market position and customer loyalty.

# Recommendations
Maven Market should focus on the following areas to optimize its performance:

* Increase Customer Retention: While sales are up by 5.6%, the higher return rate (2.9%) suggests room for improvement in product quality and customer satisfaction. Maven Market should focus on improving the quality of products with higher return rates, to minimize returns and increase customer loyalty.
* Onboarding Campaigns and Incentives for First Purchases: Create welcoming campaigns with introductory discounts or promotional offers tailored for first-time customers. Additionally, provide free trials, small product samples, or targeted discounts specifically aimed at inactive customers. These initiatives will encourage initial purchases and help convert inactive customers into loyal buyers.
* Optimize Marketing Efforts: With lower-income customers driving a significant share of the revenue, Maven Market should focus on affordability in marketing campaigns and product offerings, tailoring them to meet the needs of customers in the $10,000 to $50,000 income bracket.
* Leverage Strong Sales in Mexico: Mexico's 30% growth in sales and profit should be analyzed and leveraged by replicating successful strategies from Mexico across other regions, particularly the USA and Canada.
* Implement Targeted Strategies for Store Types: Given that the Small Grocery store type has zero returns but low sales, Maven Market should assess ways to increase sales while maintaining its high customer satisfaction rate. For the Deluxe Supermarket type, efforts should focus on replicating its success in other stores to further improve sales and profit.
* Focus on Weekend Sales: Store 8 in Merida's performance on weekends should be analyzed to develop targeted weekend promotions or sales strategies across all stores, particularly in regions with underperforming sales.



