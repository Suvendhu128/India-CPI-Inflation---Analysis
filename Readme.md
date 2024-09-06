##India CPI Inflation
Overview: In India, the Consumer Price Index (CPI) is used to measure inflation, and it involves a fixed basket of goods and services. This basket is comprehensive and includes a wide array of items that an average Indian consumer uses. These items are not limited to just food and clothing but extend to transportation, medical care, electricity, education, and almost every other category that involves expenditure of money. The CPI is calculated by comparing the general price level in the markets during a particular time period with a base year. The items in the CPI basket are classified across various categories like food and beverages, clothing, housing, fuel and light, and recreation, among others.

The CPI basket contains categories like food and beverages, housing, apparel, transportation, medical care, and more. The weight of each category in the total index might differ based on its relative importance to the average consumer expenditure but for the purpose of this analysis consider equal weights across all categories.

Dataset:
•	The dataset provided is a CPI inflation index extracted from the GOI website.
•	Each number represents the index value for that month and category.
•	There are missing values in the dataset; use suitable imputation techniques (like moving averages) if required.
CPI (Consumer Price Index) Information:
•	The CPI is an index and not a direct measure of price levels. It serves as a relative indicator to measure inflation or the average change in prices over time.
•	Consumer Price Index (CPI) values cannot be summed across different months to derive meaningful insights or aggregate measures.
•	Different types of CPI:
o	CPI-U (Urban): Reflects spending patterns for urban consumers.
o	CPI-R (Rural): Reflects spending patterns for rural consumers.
o	The General Index gives the overall inflation for the month, combining all categories.
Problem Statement: You are working with the National Statistical Office, which releases inflation numbers in India. As an analyst, you have CPI data and need to find insights. Answer the following questions:
1.	Contribution of Broader Categories to CPI:
o	Identify the contribution of different broader categories (food, energy, transportation, education, etc.) towards the CPI basket.
o	Create broader categories by combining similar subcategories (e.g., Meals, Beverages, Cereals into “Food”).
o	Calculate contributions to ensure they add up to 100%.
2.	Trend of Y-o-Y Inflation (Starting 2017):
o	Create a graph showing Y-o-Y inflation.
o	Identify the year with the highest inflation rate.
o	Investigate reasons for the highest inflation.
3.	Monthly CPI Variance in Highest Contributing Category:
o	Analyze variance in monthly CPI numbers across the highest contributing category.
o	Focus on month-on-month changes.
4.	Comparison of MoM Inflation Trends:
o	Compare MoM inflation trends between specific years.
o	Highlight any significant differences.

