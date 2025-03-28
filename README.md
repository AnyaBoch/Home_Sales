# Home_Sales
### Module 22

In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.
____________________________

**Using SparkSQL we have answered following questions:**

- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

| year_sold | avg_price  |
|-----------|-----------|
| 2019      | 300263.7  |
| 2020      | 298353.78 |
| 2021      | 301819.44 |
| 2022      | 296363.88 |

- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

| date_built | avg_price  |
|------------|-----------|
| 2010       | 292859.62 |
| 2011       | 291117.47 |
| 2012       | 293683.19 |
| 2013       | 295962.27 |
| 2014       | 290852.27 |
| 2015       | 288770.30 |
| 2016       | 290555.07 |
| 2017       | 292676.79 |

- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

| date_built | avg_price  |
|------------|-----------|
| 2010       | 285010.22 |
| 2011       | 276553.81 |
| 2012       | 307539.97 |
| 2013       | 303676.79 |
| 2014       | 298264.72 |
| 2015       | 297609.97 |
| 2016       | 293965.10 |
| 2017       | 280317.58 |

- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? 

| view | avg_price   |
|------|------------|
| 100  | 1026669.50 |
| 99   | 1061201.42 |
| 98   | 1053739.33 |
| 97   | 1129040.15 |
| 96   | 1017815.92 |
| 95   | 1054325.60 |
| 94   | 1033536.20 |
| 93   | 1026006.06 |
| 92   | 970402.55  |
| 91   | 1137372.73 |
| 90   | 1062654.16 |
| 89   | 1107839.15 |
| 88   | 1031719.35 |
| 87   | 1072285.20 |
| 86   | 1070444.25 |
| 85   | 1056336.74 |
| 84   | 1117233.13 |
| 83   | 1033965.93 |
| 82   | 1063498.00 |
| 81   | 1053472.79 |

## Acknowledgments  

During this homework, I used assistance from ChatGPT and the Xpert Learning help tool to complete the tasks and improve my understanding of the concepts. 
