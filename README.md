# pandas-challenge-1
Week 4 Challenge

# Functionality:
This dataframe ingests a csv file containing 54,639 order transactions. It futher identifies the top three categories of orders, the subcategory with the greatest number of orders, and the top five most active clients. In addition, the original file is augmented with shipping cost, total cost, total sales price with tax, and total profit columns. Finally, the top five clients and their corresponding contribution to items purchased, shipping paid, total price, and total profit are displayed professionally.

![Screenshot](top_5_client_summary.png)

# Approach:
1. The first step, *explore*, was to review the raw data, ingest the file, and then investigate that data within a dataframe to identify categories, subcategories, and clients. 
2. In the next step, *transform*, the dataframe was updated to contain various calculations to provide profitability insight into the most active clients. 
3. The third part of the design, *confirm*, was to validate calculations against selected receipt data. 
4. The last step in the design was to *summarize and analyze*.

# Summary of Findings:
The data showed that the top five most active clients purchased 496,628 items, generated $123,556,060 in revenue, and contributed $48,045,451 to profit. A single client generated 48.3%, 66.6%, and 76.1% of those amounts respectively. There is significant concentration risk in the one single client.

# Plagerism Statement:
No specific code was copied but the sources below were referenced for examples and syntax. 

# Sources:

Applying lambda row on multiple columns pandas. (n.d.). Stack Overflow. Retrieved April 4, 2024, from https://stackoverflow.com/questions/51080174/applying-lambda-row-on-multiple-columns-pandas

Faculty, K.-S. C. (n.d.). Introduction to python. Introduction to Python. https://textbooks.cs.ksu.edu/intro-python/01-basic-python/index.html 

Harrison, M. (2021). Effective Pandas: Patterns for Data Manipulation. Matt Harrison.

Lutz, M. (2013). Learning python: Powerful object-oriented programming. " O'Reilly Media, Inc.".

 Pandas groupby and apply aggregate function across rows. (n.d.). Stack Overflow. Retrieved April 4, 2024, from https://stackoverflow.com/questions/71209619/pandas-groupby-and-apply-aggregate-function-across-row 
