# Challenge_2

## Overview of Project

### Overview

Steve wants to analyze historical stock's return for several companies (tickers) to be able to provide an investment recommendation to his parents. For this purpose, Steve has historical information (2017 & 2018) for 12 market stocks: Open, High, Low, Close, and Adjusted Close prices for different dates and the respective commercialized volumes for each date. 

At a first glance, we created a VBA Program for this analysis, nevertheless, we believe the program can be modified to be more efficient when we want to analyze bigger data sets and years.  

### Project

The first part of the project is to analyze the trends of the stock to identify potential investment recommendations for Steve's parents (this could also be achieved with the previous program). The second part of the project is to review and adjust the VBA program to reduce processing time as much as possible by implementing a more efficient data analysis process. Our previous program reviews the full basis each time to compute the needed data for each stock, the proposal is to review only the needed rows, this would be implemented through the inclusion of conditional analysis. 

## Results

### Financial

2017 and 2018 returns were highly different for the analyzed stocks, the only stocks with positive returns during both years were ENPH and RUN, thus, these seem to be interesting options to invest in. Considering the average of both years, Tier 2 options would be SEDG and DQ, nevertheless, note DQ's volume is kind of low, thus, this may be a not liquid asset to purchase: 

Resources/VBA_Challenge_Comparison.PNG


### Program 

After implementing conditional analysis to optimize the flow, the adjusted program reduced ~25% computation time vs the original program. 

Resources/VBA_Challenge_2017.PNG

This amount is not significant for a program that is executed in 1 second, nevertheless, this may be hours for a larger amount of Data if, for example, we would like to analyze all the stocks in New York Exchange for the last, let's say, 10 years. 

Resources/VBA_Challenge_2018.PNG

## Summary

This week's challenge was to optimize a program built to analyze 12 stocks for a 2 years period by implementing some conditional analysis to reduce not useful computation and also by including arrays to substitute independent variables. 

From a computational perspective, results showed a 25% reduction in computation time while from a financial perspective, needing more information to provide an accurate recommendation, we identify ENPH and RUN stocks as consistently showing positive returns. 
