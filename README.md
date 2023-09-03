# home-price-index-analysis
US Case-Shiller Home Price Index has been analysed in this code, based upon several factors which play important role in its determination.

# Datasets:
The data collected for this assignment consist of two main files: Supply and Demand.
These datasets contain quarterly data on key supply-demand factors that influence US home prices nationally.

### Supply File:
    1. DATE: The date of the observation. (2003 - 2023)
    2. PERMIT: New Privately-Owned Housing Units Authorized in Permit-Issuing Places: Total Units (Thousands of Units, Seasonally Adjusted Annual Rate). This variable represents the number of new housing units authorized for construction in permit-issuing places.
    3. MSACSR: Monthly Supply of New Houses in the United States (Seasonally Adjusted). It indicates the monthly supply of new houses available in the United States.
    4. TLRESCONS: Total Construction Spending: Residential in the United States (Millions of Dollars, Seasonally Adjusted Annual Rate). This variable represents the total construction spending on residential projects.
    5. EVACANTUSQ176N: Housing Inventory Estimate: Vacant Housing Units in the United States (Thousands of Units, Not Seasonally Adjusted). It provides an estimate of the number of vacant housing units in the United States.
    6. CSUSHPISA: S&P/Case-Shiller U.S. National Home Price Index (Index Jan 2000=100, Seasonally Adjusted). This variable serves as a proxy for home prices and represents the home price index for the United States.
### Demand File:
    1. INTDSRUSM193N: Interest Rates, Discount Rate for United States (Billions of Dollars, Seasonally Adjusted Annual Rate). This variable represents the interest rates or discount rates for the United States.
    2. UMCSENT: University of Michigan: Consumer Sentiment. It measures the consumer sentiment index based on surveys conducted by the University of Michigan.
    3. GDP: Gross Domestic Product (Billions of Dollars, Seasonally Adjusted Annual Rate).
    4. MORTGAGE15US: 30-Year Fixed Rate Mortgage Average in the United States (Percent, Not Seasonally Adjusted). It indicates the average interest rate for a 30-year fixed-rate mortgage.
    5. MSPUS: Median Sales Price of Houses Sold for the United States (Not Seasonally Adjusted)
    6. CSUSHPISA: S&P/Case-Shiller U.S. National Home Price Index (Index Jan 2000=100, Seasonally Adjusted). This variable serves as a proxy for home prices and represents the home price index for the United States.

### Data Cleaning and Preprocessing:
Please the data before applying it to the model, as per your accordance.

### Visualization:
Found the correlation between features and target variable.
Prepared Bar charts and Line Charts.

### Build Model:
Checked the models efficiency for the given problem statement and then selected one of them. The best one was Linear Regression Model.
    Linear Regression,
    Decision Tree,
    Random Forest,
    Support Vector Regression,
    Neural Network

### Evaluate Model:
Evaluation done on various parameters such as accuracy matrix, R2 Score etc.

### Conclusion:
Based on the correlation analysis and the coefficients from the Linear Regression model, several key insights can be derived:

    1. Supply factors, such as house inventory and the number of authorized housing units, have a positive influence on home prices. Higher construction spending on residential projects also contributes significantly to higher home prices.

    2. Demand factor, such as mortgage interest rates, have a negative impact on home prices. Higher mortgage rates and lower consumer sentiment are associated with slightly lower home prices.

    3. Economic factors, including GDP and interest rates, play a crucial role in determining home prices. A strong economy with higher GDP and slightly lower interest rates tends to support higher home prices.

    4. The median sales price of houses sold is strongly correlated with home prices, reflecting the importance of market dynamics and buyer behaviour in determining home price movements.

    5. These insights can be valuable for various stakeholders in the real estate market, including home buyers, sellers, developers, and policymakers. Understanding the factors that influence home prices can help make informed decisions related to investments, financing, and economic policies.
