# Global-SuperStore-Sales-Analysis

_Requirements_

1. Programming language: Python

_Libraries_

1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn 

## Introduction
A global superstore has given us the task to identify what works best for them in terms of sales and making profit. 
Using exploratory data analysis (EDA) we will help them identify:

1. Their most and least profitable product categories

2. Segment analysis of sales and profit

3. Geographical analysis of sales and profit

4. Performance trend over the years

Given the insights gained from the EDA, the superstore can choose to remove non-profitable products or invest in marketing efforts for products,
segments and geographical areas that are driving their profit.

## Insights

### Findings
1. Categories and sub categories.
The three categories all account for over 30% of sales. Technology-37.5%, Furniture-32.5%, Office Supplies 30%. 
Technology accounts for the highest total profits (almost half) at 45.2%. Office supplies profits are at 35.3% while furniture is at 19.4% profit. 
Why do furniture contribute to such low profits yet has high sales?
Furniture category has 4 subcategories ('Furnishes', 'bookcases', 'chairs', and 'tables') 
Only 'Furnishes' (12.2%) has a profit margin above the average profit margin of sub-categories (11.6%).
Bookcases has an 11% profit margin, and chairs 9.3%. Tables sub-category is infact making a loss. It records a -8.5% profit margin. 
This is where Global Superstore is losing money.

2. Segments
Global superstore has three main segments. Consumer, Corporate and Home office. The consumer segment accounts for over 6.5Million dollars in sales 51.5%.
Corporate 30.3% while Home Office 18.3%. Profit margins among the segments is almost equal. 
Both consumer and corporate have 11.5% profit margins. Home Office segment has a 12.5% profit margin. 
In all segments, sale demand decreses from technology, furniture and office supply in that order.

3. Geographical Markets
Gobal stores largest market is APAC. The Asia Pacific market at 2938.1K, The US market 2164.6K, EMEA 783.8K, 
Canada $66.9K. Canada has the lowest sales but highest percent profit margins among the markets.
Global stores has a presence in major markets with profit margins mainly ranging between 10 to 14%.
EMEA market has an uncharacteristic low profits and lower profit margin than the rest of the markets.

4. Time series
Global stores has experienced growth in sales and profits gradually from 2011 to 2014. If this trend continues, the future is bright for the business.

### Limitations
The data lacks population numbers for the different regions. Demographic information would have let us know markets where Global store is most popular 
and markets where more advertising and marketing needs to take place. Markets with high populations are likely to record high sales by default. This however doesn't represent the actual market share in comparison with key competitors.

### Recommendations
From the analysis, the tables sub-category is making losses. 
Only 20 out of 170 table types generate a profit margin that is higher than the company's average profit margin. 
Global stores can continue selling the 20 profitable unique tables. On the other hand, 
the loss making tables can be gradually removed from the online shelfs for higher profitability.
