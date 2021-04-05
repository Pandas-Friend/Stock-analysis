# Stock Analysis
## Overview
Throughout this module we were trying to create a sub routine that analyzed the stocks of 12 different companies over the years 2017 and 2018. The sub routine we created looped through all the stocks after a year input was entered into an input box by the user (either 2017 or 2018) and gave us the total daily volume and the return percentage for the year of all 12 stocks. To make it as easy as possible for the user we included a button that the user could click to run the analysis without having to do anything in the visual basic editor, and we also included a button to clear the worksheet.  
Although our code worked fine analyzing just 12 stocks it would probably face some difficulties analyzing all the stocks in the market. For the challenge we refactored our code to make it run more efficiently and quicker. With the refactored code the user should have no problem analyzing as many stocks as they desire much more quickly than the old code would have allowed.
## Results
	There were some major differences between the stock performances of 2017 and 2018. The overall performance of the stocks was much better in 2017 with all the stocks having a positive return besides one stock. Four stocks in 2017 even had returns over 100 percent. 

![Stocks2017](Class/Module2/Stocks2017.png)

 In 2018 only 2 stocks had a positive return, and of the two stocks with a positive return only one performed better than it did in the previous year. The one negative stock from 2017 also improved in 2018, but it remained negative. 

![Stocks2018](Class/Module2/Stocks2018.png)

The refactored code performed much better than the original code, with the original code running in 5.01 and 6.10 seconds, and the refactored code running in 0.83 and 0.75 seconds for 2017 and 2018, respectively.

![Time2017](Class/Module2/Time2017.png)

![Time2018](Class/Module2/Time2018.png)

![VBA_Challenge_2017](Class/Module2/Resources/VBA_Challenge_2017.png)

![VBA_Challenge_2017](Class/Module2/Resources/VBA_Challenge_2017.png)

In order to make the refactored code more efficient we created 4 different arrays: tickers, tickerVolumes, tickerStartingPrices, and tickerEndingPrives. The tickers array created a ticker symbol for the stock, and we created a tickerIndex variable to match the other arrays. Using the variable, we could assign all three of these arrays to the ticker symbols. This helped the code run much faster.

![Original_Code1](Class/Module2/Original_Code1)

![Original_Code2](Class/Module2/Original_Code2)

![Refactored_Code1](Class/Module2/Refactored_Code1)

![Refactored_Code2](Class/Module2/Refactored_Code2)

## Summary
	The most obvious advantage to refactoring code is that it runs much faster as shown above. Refactored code is also usually easier to understand. The disadvantage to refactoring code is that it can take up a lot of time to modify code that already runs without any bugs. For our script, the advantage of the code running faster was on full display with the refactored code running much faster. The disadvantage was that it took me hours to refactor it and when only running an analysis on 12 stocks saving a few seconds is not really worth it, but when Steve applies this to a thousand or more stocks the extra time put in refactoring will definitely be worth it.
