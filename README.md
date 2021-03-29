# Stock Analysis

## Overview of Project
To refactor the existing 'Stock Analysis' code so that Steve can continue his stock research for his parents by expanding the dataset to include the entire stock market over last few years. The existing code is restricted to only to do analysis only on few thousands of stock and not scalable to the entire stock market. 


## Analysis and Challenges
    The analysis was focused on the following two criteria:
    1. Stock data presented for year 2017 and 2018
       The stock data presented are arranged in ascending order for both 2017 and 2018. This gave more opportunity to build the efficient code.	

    2. Existing Code:
        a. While looking at the existing code, it was observed that there were nested for loops that could be easily avoided to provide better run times.
		b. The inner loop contains calculations for 'total volume', 'ticker starting price' and 'ticker ending price' gets executed  'no of tickers' * no of rows of the corresponding year worksheet' times which is expensive
		
## Challenges:
    1. To match the output before and after refactoring the code
    2. To ensure the refactor code performs better than the current code
	3. The refactor code is well documented so that it is easily readable for any user.

## Results

- After refactoring the code performs better when compared to the original code. Please refer to the below links for your perusal.
   - https://github.com/rthirukachoor/stock-analysis/blob/main/Resources/VBA_Challenge_2017.PNG
   - https://github.com/rthirukachoor/stock-analysis/blob/main/Resources/VBA_Challenge_2018.PNG
   - https://github.com/rthirukachoor/stock-analysis/blob/main/Resources/OriginalCodeRunTime_2017YearAnalysis.PNG
   - https://github.com/rthirukachoor/stock-analysis/blob/main/Resources/OriginalCodeRunTime_2018YearAnalysis.PNG

- Advantages of Refactored Code:
  1. The analysis can scale to larger dataset to include the entire stock market over last few years
  2. Code is clean and easily to understand
  3. Better performance and rendering time is much better
  4. Better user experience

- Disadvantages of Refactored Code:
  1. Effort involved to refactor the code
  However, this outweights the benefits that is gained through this refactoring activity.






