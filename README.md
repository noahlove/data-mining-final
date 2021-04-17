---
output:
  html_document: default
  word_document: default
  pdf_document: default
---
# data-mining-final
Author: Noah Love, Blinda Tian

### Project summary
- A at most 5 sentence summary of the project
- An general explanation of the different files/folders if someone were to replicate your study.

(predict interest rate change? or inferences? work on time series)
generating possible features, then to predict 


(or we can use infer whether the US economy has gone through a short or long economic cycle using clustering/k-means) 


assess the impact on interest rate with respect to each of the proposed financial variables and to demonstrate the level and when the effects are observed strongly. In order to gain an comphrehensive analysis, we employ two methods, the cluster analysis and linear regression. In conjuture with two methods, we hope to deliver a deeper analysis.  



## Introduction
- intent and finding 
- have at least one paragraph that discusses the potential for data-snooping for your project.

The low-interest rate has been the world Central Bank's monetary policy since the Covid pandemic hit when they intended to stimulate the overall economy. With economic activity gaining momentum in recent months and the approval of a third U.S. stimulus package in March, the current U.S economy is stronger than expected and  higher inflation and thus wall street has spread out concerns over an interest rate hike soon in the future. In short, the unpredecented stimulus package has drived up the market and this has left investors wondering what will the interest rate in the future. In this study, our project aim to investigate the main drivers for the 10 year interest rate and discover its relation to other economic indicators and financial variables. 


( 10 year interest rate definition add here....)
For this study, we will mainly investigate 10 year treasury yield. (what can it serve,purpose,why important,etc)



The algorithm will helps to discover the pattern over characteristics of 10 year risk-free rate in economic cycle stages. The pattern can be used in (....)
The output can provide information for individual investors or financial institutions to understand about financial market and shed some light on interest rate prediction. 






The mechanism of monetary policy (data classification): 

1. Asset price: 
- intent and finding 
- house_price_index_nationwide
- s_and_p
- total_vehicle_sales


2. Debt supply and demand: 
- federal_debt_percent_of_gdp
- federal_surplus_or_deficit

3. economic expectation/confidence:
- consumer_price_index_nationwide
- consumer_price_index_urban
- personal_savings_rate
- personal_consumption_expenditures
- gdp
- real_gdp
- real_gdp_per_capita
- all_employees_minus_farm
- unemployment_rate
- industrial_production_index
- labor_force_participation_rate
- inflation_expectation

4. secondary market 
- ten_minus_three_months_treasury
- ten_year_treasury
- aaa_corporate_bond_yield
- ten_minus_two_treasury
- thirty_year_fixed_mortgage

5. Federal Reserve (Fed decided)
- m_one
- m_two
- m_three
- velocity_of_mtwo
- eff_fed_funds_rate



## Dataset
- APIs grab
- data processing

The dataset can be obtained from the Federal Reserve Bank of St. Louis FRED Database and Yahoo Finance.
The analysis will be conducted using packages like quantmod (.....) 







## Algorithm

- what drives up interests rate, real underlying factors?
clustering 

pattern discover 


## Validation
access model accuracy

## Conclusion
- intent and finding 


xx  is the dominate variable for explaining the 10 year yield.


(back to 10 yr function)

## Final checklist (for reference)
To complete this portion, I recommend you talk to each other before the full project is finished.

What was the initial motivation for tackling the project?
What datasets were used?
What aspect of the project is considered a data-mining and what is discovered?
Is there anything you would have done differently? For example
Used different datasets
Used different models to explore the data
Generated a different feature
Arrived at a different conclusion from the given data. (These are simply suggestions, you team only has to come up with one thing




## Datasets
The data sets are difficult to keep track of by themselves. They have to each be downloaded separately. As a result, each is listed here for reference:

consumer_price_index_urban: Consumer Price Index for All Urban Consumers: All Items in U.S. City Average (CPIAUCSL)	
https://fred.stlouisfed.org/series/CPIAUCSL


inflation_expectation: University of Michigan: Inflation Expectation (MICH)

ten_year_treasury: 10-Year Treasury Constant Maturity Rate (DGS10)	

https://fred.stlouisfed.org/series/DGS10

ten_minus_two_treasury: 10-Year Treasury Constant Maturity Minus 2-Year Treasury Constant Maturity (T10Y2Y)

https://fred.stlouisfed.org/series/T10Y2Y

ten_minus_three_months_treasury: 10-Year Treasury Constant Maturity Minus 3-Month Treasury Constant Maturity (T10Y3M)

https://fred.stlouisfed.org/series/T10Y3M

unemployment_rate: Unemployment Rate (UNRATE) 

https://fred.stlouisfed.org/series/UNRATE

real_gdp: Real Gross Domestic Product (GDPC1)	
https://fred.stlouisfed.org/series/GDPC1


eff_fed_funds_rate: Effective Federal Funds Rate (FEDFUNDS)	

https://fred.stlouisfed.org/series/FEDFUNDS

gdp: Gross Domestic Product (GDP)	

https://fred.stlouisfed.org/series/GDP

thirty_year_fixed_mortgage: 30-Year Fixed Rate Mortgage Average in the United States (MORTGAGE30US)	

https://fred.stlouisfed.org/series/MORTGAGE30US


velocity_of_mtwo: Velocity of M2 Money Stock (M2V)

https://fred.stlouisfed.org/series/M2V

s_and_p: S&P/Case-Shiller U.S. National Home Price Index (CSUSHPINSA)

https://fred.stlouisfed.org/series/CSUSHPINSA

m_one: M1 Money Stock (M1SL)

https://fred.stlouisfed.org/series/M1SL

m_two: M2 Money Stock (M2SL)

https://fred.stlouisfed.org/series/M2SL

federal_debt_percent_of_gdp: Federal Debt: Total Public Debt as Percent of Gross Domestic Product (GFDEGDQ188S)

https://fred.stlouisfed.org/series/GFDEGDQ188S

all_employees_minus_farmers: All Employees, Total Nonfarm (PAYEMS)

https://fred.stlouisfed.org/series/PAYEMS

personal_savings_rate:  Personal Saving Rate (PSAVERT)

https://fred.stlouisfed.org/series/PSAVERT

aaa_corporate_bond_yield: Moody's Seasoned Aaa Corporate Bond Yield (AAA)

https://fred.stlouisfed.org/series/AAA

personal_consumption_expenditures: Personal Consumption Expenditures (PCE)

https://fred.stlouisfed.org/series/PCE

industrial_production_index: Industrial Production: Total Index (INDPRO)	

https://fred.stlouisfed.org/series/INDPRO

federal_debt_total: Federal Debt: Total Public Debt (GFDEBTN)

https://fred.stlouisfed.org/series/GFDEBTN

labor_force_participation_rate: Labor Force Participation Rate (CIVPART)

https://fred.stlouisfed.org/series/CIVPART

consumer_price_index_nationwide: Consumer Price Index: Total All Items for the United States (CPALTT01USM657N)

https://fred.stlouisfed.org/series/CPALTT01USM657N

gold_price: Gold Fixing Price 10:30 A.M. (London time) in London Bullion Market, based in U.S. Dollars (GOLDAMGBD228NLBM)

https://fred.stlouisfed.org/series/GOLDAMGBD228NLBM

m_three: M3 for the United States (MABMM301USM189S)	

https://fred.stlouisfed.org/series/MABMM301USM189S

real_gdp_per_capita: Real gross domestic product per capita (A939RX0Q048SBEA)	

https://fred.stlouisfed.org/series/A939RX0Q048SBEA

federal_surplus_or_deficit: Federal Surplus or Deficit [-] (FYFSD)

https://fred.stlouisfed.org/series/FYFSD

house_price_index_nationwide:  All-Transactions House Price Index for the United States (USSTHPI)	

https://fred.stlouisfed.org/series/USSTHPI

total_vehicle_sales: Total Vehicle Sales (TOTALSA)
