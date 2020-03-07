# Module 2 Challenge: VBA-Stock-Analysis
Analysis of 12 green stocks starting price, ending price, and total volume for 2017 and 2018 with macros. 

The refactored macro will now handle large datasets more efficiently. Previously, the macro looped through the entire dataset for each ticker, in this case looping 12 times over the 3012 rows for a total of 36, 144 loops. After editing the code to loop through just once and storing the data in three separate arrays: startingPrice, endingPrice, and volumes, the macro has 91.6% less data to loop through. This will be beneficial to Steve as he plans to analyze the entire stock market.





