# (Future Group Exercise)
## by (Khaled Yaseen)


## Dataset

> I used dataset from Future-Group for translation and localization services, this smaple data is an exercise in hiring process for Data Analyst role in the company. 
Data set contains information about sample of 99 observations and including 15 different variables like Account_ID, Account Class, Last Year Growth Indicator, Profitability, Historical and last year Revenues, and other atrractive information to be explored.


## After loading data from XLSX file of Future Group Exercise Dataset, i started assessing data visually and programatically to be cleaned and I found some limitations i need to handle it before starting analysis , for instance: 

- Convert Account ID to string.
- Convert Last Year Growth Indicator to category.
- Convert Account Class to category.
- convert account class = 0 to nan.
- Profitability = -999.99 or 100 is weird and usual so i preferred to convert it to nan not to drop because it has important observation in historical revenues.
- I have doubts about the records of observations which are nan in Last Year Growth Indicator and Profitability and 0 in Historical Revenue so i preferred to convert their Historical Revenue to nan.
- Convert Total open opportunities_USD = 0  to nan as it unlogic.
- Drop the account id = 12343 as it has not data to be explored.


## I decided to export the cleaned data to tableau where I can do the explanatory process and I got great insights and findings. You can find Tableau dashboards through this link: https://public.tableau.com/app/profile/khaled.yaseen/viz/Future-GroupExercise/AccountClassGrowthindicator?publish=yes. 
## Here are the insights I found:

 1 : The Account with ID: 520 is the most important customer and has a huge gap from other accounts. Its historical revenues ~= 1700000, In the last year company gained from it ~= 2000 and it is small number comparing to other top accounts and its historical revenues so its Last Year Growth Indicator decreased.

 2 : The Account with ID: 12334 is the first account in the last year revenues and has revenues ~= 49000 with a huge gap from the second account with ID: 10890 which have revenues ~= 26000. And this is only its first year with the company so it is a good start to grow investment with it.

 3: The Account with ID: 10890 has the most service 2 order count in the last year with 8179 orders then the account ID: 520( Historically the most important customer) with 7248 orders.

 4: The Account with ID: 10870 has the most service 2 order count in the last year with 100 orders then the account ID: 520 -Historically the most important customer- with 33 orders. 
 
 5 : The Account with ID: 10885 has the most service 3 order count in the last year with 178 orders then the account ID: 11751 with 159 orders. Note: the two accounts are CLASS B.

 6 : Only account with ID: 12334 -the first account in the last year revenues- has service 4 order count in last year with 7 orders.

 7 : There is no accounts has service 5 order count in the last year.

 8 : The highest and the lowest accounts in profitability are in the lost category in the last year growth indicator and have low revenues but in general the lost last year growth indicator is the smallest in avg last year growth profitability. the highest account is: 12327 with profitability = 96.4 and the lowest is: 11845 with profitability = -63.8.

 9 : The highest account in total open opportunities is: 11751 with total open opportunities = 549000.

 10 : Class C is the most class represented in data with percentile 52.73% of total classes and has the highest avg profitability with 62.66. 

 11 :  Class A is the highest class in historical revenues with percentile 64.14% of total historical revenues for classes.

 12 : Last year growth indicator: Lost is the highest indicator in data with percentile 60.76% of total indicators so company should solve this problem to keep customers.

 13: Last year growth indicator: decreased is the highest indicator in historical revenues percentiles with percentile 52.49% of total indicators so company should do its best to make the highest indicator: increased.

 14 : Last year growth indicator: increased has the highest avg profitability slightly different to other indicators. incresed = 59.3 , decreased = 58.7 , lost = 57.0.

 15 : Account class: C and Last year growth indicator: decreased is the most case occur but has small revenues comparing to class: A Whether it increases or decreases in Last year growth indicator but But surprisingly, this account class: C and Last year growth indicator: decreased is higher than all cases for class: B.

 16 : Service 1&2&3 order counts has a positive relationship with revenues.

 17 : Monthly and quarterly order counts for Account class: A,  almost has a positive relation with revenues. and for weekly order count it is a positive relationship but the revenues reduce from weekly order count 49 to 51. and account classes: B&C also have a positive relation with revenues.

 18 : Profitability has a small negative relationship with revenues and that is strange for me.

 19 : I plotted a chart between service 1&2&3 order counts for easy predictions between each other.

 
## Key Insights for Presentation

 - The Account with ID: 12334 is the first account in the last year revenues and has revenues ~= 49000 with a huge gap from the second account with ID: 10890 which have revenues ~= 26000. And this is only its first year with the company so it is a good start to grow investment with it.

 - Account class: C and Last year growth indicator: decreased is the most case occur but has small revenues comparing to class: A Whether it increases or decreases in Last year growth indicator but But surprisingly, this account class: C and Last year growth indicator: decreased is higher than all cases for class: B.
