# Factors Impacted home prices over the last 20 years

## Task - Using publically available data for key factors that influence US home prices nationally. Then, build a data science model that explains how these factors impacted home prices over the last 20 years.

Approach - The following variables are chosen for the study-
- Unemployment Rate
- Per Capita GDP
- Median Household Income
- Construction Prices
- CPI 
- Interest Rates
- Number of new houses supplied
- Working Population
- Urban Population
- Percentage of population above 65
- Housing subsidies
- Number of Households

As a proxy to the home prices, S&P CASE-SHILLER Index is used. 

ALL data Source[https://fred.stlouisfed.org/].

Data for all the variables is downloaded, preprocessed and combined to create a datset. Data for different variables had different frequencies. So, to combine the data, necessary interpolations are made.

Linear Regression is used as most of the variables have high correlation with the target variable.
