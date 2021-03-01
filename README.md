# VBA of Wall Street
# Overview of Project
The purpose of this project is to analyze 2017 and 2018 all stocks performance using the visual basic application. Using the refactoring code to determine whether refactoring code would make VBA scrip run faster and yeilds a better result.

# Results
To get to the result I use for loop to loop through arrays (tickers, tickerVolumes, tickerStartingPrices, and tickerEndingPrices) to output the “Ticker,” “Total Daily Volume,” and “Return” columns in the spreadsheet.Then I use the If-then to check if current row is the first row or last row with the selected TickerIndex.  If the TickerIndex is in the first row assign the current closing price to the tickerSatrtingPrice and If it is in the last row assign the current closing price to the tickerEndingPrice. In addition I use the refactoring code to measure performance.  
<br/> Bases on the analysis 2017 is a good year to invest. The highest return in year 2017 is 199.4% for DQ corp and the lowest is -7.2% for TERP.  However 2018 is not a good year to invest.  Based on the all stocks analysis for 2018 almost all stocks have a negative return except for ENPH and RUN. Considering overall results, it would be better to go with ENPH stocks as it has the most favorable result (132% & 82% over two years.)
<br/>![2017 AllStocksAnalysis.png](https://github.com/xujenny98/VBA_Challenge/blob/main/Resource/2017%20AllStocksAnalysis.png) ![2018 AllStocksAnalysis.png](https://github.com/xujenny98/VBA_Challenge/blob/main/Resource/2018%20AllStocksAnalysis.png)
<br/> As for the refactoring of the script, this improved the performance, as the previous code took 1.040 seconds whereas the new code takes only 1.023 seconds and 1.040 to 1.031 for 2017 and 2018 respectively. Therefore, it is better using the refactored code.
<br/> ![VBA_Challenge2_2017.png](https://github.com/xujenny98/VBA_Challenge/blob/main/Resource/VBA_Challenge2_2017.png)![VBA_Challenge_2017.png](https://github.com/xujenny98/VBA_Challenge/blob/main/Resource/VBA_Challenge_2017.png)
<br/> ![VBA_Challenge_2018.png](https://github.com/xujenny98/VBA_Challenge/blob/main/Resource/VBA_Challenge_2018.png) ![VBA_Challenge2_2018.png](https://github.com/xujenny98/VBA_Challenge/blob/main/Resource/VBA_Challenge2_2018.png)

# Summary
The advantage of refactoring code which it improves internal structure without changing or adding to its external behavior and functionality. In terms of this particular analysis it really improved the result when we refactored the code. However the disadvantage of using the refactoring is that if we change the dataset structure or insert any columns in between, it will show incorrect results as the information it is picking up is hardcoded and thus will not reflect what the user needs.


