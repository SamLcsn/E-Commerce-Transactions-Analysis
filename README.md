# E-Commerce Transactions

### EXPLORATORY DATA ANALYSIS (EDA): Executive Summary
*(using Microsoft Power BI)*
![Online_Retail_EDA_PowerBI](https://github.com/user-attachments/assets/0eb55ca7-fed3-43dc-84d1-47cf8b0dc04d)





### DATA CLEANING SUMMARY
*(using Python)*

*  533, 678 total rows on Working Dataset (previously 541,909)
*  4, 202 rows are matching transactions of placement orders (+ postive in 'Quantity' value) that
were eventually cancelled (- negative in 'Quantity' value)
*  8, 231 rows were removed (1.52% of the raw dataset)
    >  12 rows were zero in 'UnitPrice' and null in both 'Description' and
'CustomerID'; they have insufficient information

    >  5,270 were duplicate rows

    >  2,689 rows with alphameric StockCodes; identified as postage and bad debt
records; deemed not relevant to the transaction analysis of retail products.

    >  147 rows with alphanumeric StockCodes; identified as carriages and ebay;
deemed not relevant to the transaction analysis of retail products.

    >  1 row with the 'throw away' product description have been removed

    >  4 rows with the 'thrown away' product description have been removed

    >  6 rows with the 'Unsaleable, destroyed.' product description have been
removed

    >  1 row with the 'thrown away-can't sell' product description have been removed

    >  1 row with the 'Thrown away-rusty' product description have been removed




