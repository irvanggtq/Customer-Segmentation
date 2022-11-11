# Customer Segmentation
# Workflow Customer Segmentation
1. Use Case
2. Business Understanding
3. Data Understanding
4. Data Preparation
5. Data Profiling
6. Data Cleansing
7. Exploratory Data Analysis
8. Preprocessing Modeling - RFM
9. Modelling - RFM
10. Labeling
11. Result
12. Recommendation
# Exploratory Data Analysis
- How much monthly revenue in 2011-2014?

  ![newplot (1)](https://user-images.githubusercontent.com/113869968/201445272-099f359c-3646-43b3-8503-14581c286291.png)
  
  Based on the chart above, monthly revenue from 2011-2014 is **seasonal** because in certain months there is an increase and decrease. In September and November in 2011-2014 there was **always a fairly high increase** in income, this may be due to the high demand for products for the Halloween and Christmas celebration preparation.
  
# Modeling Using RFM
### Recency Frequency Monetary (RFM)

RFM is a model used in marketing analysis that segments a company's consumer base by their purchasing patterns or habits. 

- Recency : how long it's been since a customer bought something from us.
- Frequency : how often a customer buys from us
- Monetary value : the total value of purchases a customer has made.

# Preprocessing Modeling

- Create new data frame containing customer name column and recency column. This is done by calculating how long since customers make purchases.
- Create new data frame containing customer name column, frequency column, and monetary column. The results of frequency can be determined by calculating how often customers make a purchase. While the monetary is produced from the calculation of how much money the customer spent making purchases.
- Combine the recency table with the frequency and monetary table.

# Modeling
