# Python Project 1: Stock Data Analysis with Pandas and Plotly

**Author**: Chinh X. Mai, **Date**: June 28, 2022

![image](https://user-images.githubusercontent.com/89245616/177420136-236acbee-e9c5-4eaa-9b54-239375306645.png)

## Case description

Considering a hypothetical scenario, where I want to learn to invest in the stock market. To simplify the choices of stock I have to make, I will only consider the stocks in the DAX30 Index, as they are the major German blue chip companies trading on the Frankfurt Stock Exchange. The 10 components of the DAX30 index are listed in the table below

| Symbol  | Company Name                                | Last Price | Change | % Change | Volume     |
| ------- | ------------------------------------------- | ---------- | ------ | -------- | ---------- |
| SY1.DE  | Symrise AG                                  | 106.25     | 0.05   | 0.05%    | 277,156    |
| ALV.DE  | Allianz SE                                  | 181.04     | \-0.16 | \-0.09%  | 1,069,053  |
| MRK.DE  | MERCK Kommanditgesellschaft auf Aktien      | 165.1      | 0.3    | 0.18%    | 313,644    |
| DTE.DE  | Deutsche Telekom AG                         | 18.84      | \-0.04 | \-0.20%  | 6,880,550  |
| VOW3.DE | Volkswagen AG                               | 138.88     | \-0.3  | \-0.22%  | 913,070    |
| DBK.DE  | Deutsche Bank Aktiengesellschaft            | 8.89       | \-0.03 | \-0.33%  | 10,112,593 |
| HNR1.DE | Hannover Rück SE                            | 136.4      | \-0.45 | \-0.33%  | 95,892     |
| HEI.DE  | HeidelbergCement AG                         | 48.78      | 0.29   | 0.60%    | 623,977    |
| 1COV.DE | Covestro AG                                 | 34.26      | \-0.22 | \-0.64%  | 982,911    |
| BEI.DE  | Beiersdorf Aktiengesellschaft               | 98.62      | 0.64   | 0.65%    | 246,097    |

**Table 1**: 10 Components of the DAX PERFORMANCE-INDEX (source: [Yahoo! Finance](https://finance.yahoo.com/quote/%5EGDAXI/components?p=%5EGDAXI), accessed on June 27, 2022)

These are the stocks that I would like to carry out an exploratory analysis on. As I want to invest in 6 stocks, I expect that the analysis will give me enough insights to select the stocks to form a portfolio and prepare for the optimization.

## Objectives

This project aim to showcase my familiarity with Pandas and Plotly, which are the two powerful packages respectively used to manipulate data and construct interactive plots in Python. Furthermore, I would like to use the tools provided by these packages to study the trends in prices, volatility in returns, and changes in cumulative returns of these stocks. Hence, the detailed analysis will focus on

* using `Pandas` to manipulate stock data to extract useful insights
* utilize `plotly` to construct interactive plots
* investigate trends in stock prices
* study the volatility in stock returns
* visualize the cumulative returns of the chosen stocks

I will also construct many type of plots to visualize stock data, depending on their use cases as well as customize these plots so that they could deliver the intended information.

## Detailed documentation

For detailed documentation, please refer to the Github repository using the following link

[Github](https://github.com/ChinhMaiGit/Project-Python-1/)
