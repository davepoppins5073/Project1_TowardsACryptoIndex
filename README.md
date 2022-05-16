# Project-1---Active-

Prezi: https://prezi.com/p/edit/ysu92emscofq/

**Overview**

This research exercise was conducted in order to understand if we can create a model to build an investment portfolio that outperforms the S&P Broad Crypto Digital Market Index. Due to the expansive nature and copious number of investable assets in the Crypto space, and the number of variables that need to be taken into condieration while investing, it can become complex. This model and future platform, provide a safe option for investors to gain exposure to these markets while outperforming the SPCBDM.

Our idea was to understand if a combination of 2 sets of Crypto Assets produced better returns than just 1 set of Coins/Assets, without drastically increasing volatility and skewing the Risk profile of the portfolio.

In addition to the veteran coins that most people have heard of in the Cryptocurrency space, we wanted to see if Analyzing protocols in a rapidly growing DeFi sector provided some insights/value and improved our potential returns. DeFi is a rapidly growing sector within the CryptoCurrency space that has grown from about 500Million to 150Billion in 2 years. The crypto market as a whole has been in a downtrend for the better part of the last year and we wanted to see the effect of including some variety of undervalued coins into our portfolio and establish our findings.  

Please note this model pulls live prices, therefore prices may vary each time you run it.
_______________________________________________________________________________________________________________________________

**Technologies**

Our model utilizes Python (v 3.1.0) and the following libaries: 

1. pandas 
2. numpy
3. hvplot
4. os
5. MCForecastTools
6. pathlib
7. requests
8. json
9. defillama
10. dotenv
11. pandas_datareadr
12. datetime
13. matplotlib
__________________________________________________________________________________________________________________________________

**Installation Guide**

Most of the libraries listed above were part of the base applications that were installed with the Python version listed above. However, there are some individual packages and API's that need to be installed. One can refer to the Pip Package Installation Website for further support:
https://packaging.python.org/en/latest/tutorials/installing-packages/#ensure-you-can-run-python-from-the-command-line
__________________________________________________________________________________________________________________________________
**Application of the Model: **

Research: 
The first step in this process was to ensure that we utilized the relevant API's to provide us with our pricing data for the various cryptocurrencies. We utilized 3 API's throughout the research process: 
  1. CoinMarketCap API: To access the coins for Coinset A (Veteran Coins)
  2. DefiLlama API: To access the coins for Coinset B (DeFi Sector Coins)
  3. Yahoo Finance API: To access the historical data for both Coinsets as well as the data for the SPCBDM Index.

Data Cleaning: Sorting out the Datasets to fit our filtering criteria and excluding all coins that do not fit the predefined parameters.

Coinset A (Veteran Coins) Parameters: 
1. Market Cap > $15 Billion
2. Time in the market > 4 years --> 01.01.2018

Coinset B (DeFi Coins) Parameters:
1. Total Value Locked > $7 Billion
2. Market Cap > $4.5 Billion

For Coinset B: Further Calculations of Market Cap /Total Value Locked and Fully Dilluted Value / Total Value Locked to understand which coins were undervalued.

Analysis: 

We conducted analysis for Coinset A (Veteran Coins), Coinset B (DeFi Coins) & Coinset C (Combo of A + B) while comparing them to the SPCBDM Index 

- Daily Returns
- Cumulative Returns 
- Sharpe Ratio
- Standard Deviation
- Correlation
- BackTesting
- MonteCarlo Simulation
__________________________________________________________________________________________________________________________________
**Contributors & Duties: **

Planning - Kfir | Aarchit | Aliza
Management - Kfir | Aliza
Project Concept - Kfir | Aarchit
Code - Kfir | Aarchit | David
Presentation - Aliza
Speaking Points - Aliza | Donte
________________________________________________________________________________________________________________________________
**Licenses: **

No licenses were used for this project
