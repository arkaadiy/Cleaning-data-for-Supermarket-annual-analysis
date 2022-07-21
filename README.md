# Cleaning-data-for-Supermarket-annual-analysis
Cleaning data for 2018 of sales, purchases, taxes and margin from local supermarket in Poland


About the store:
Store was open in 2009 and is located in Poland. The shop area is 120m2. It offers general food-and basic chemistry, hygienic articles.
It has fresh bread from 4 different bakers, sweets, local vegetables, dairy, basic meat(ham,sausages), newspaper, home chemistry etc.

Shop is located in city that population is around 28 000 people.
Shop is placed in mid of house estate(block of flats), near is sports field.
The store has 4 employees. Work in the store takes place on 3 shifts.
Working hours: Monday-Saturday 06:00—22:00, Sunday 10:00—20:00.




  The data shows: stocking, sales, sales statistics, characteristics of products sold from January 2018 - December 2018.
All currency amounts are in PLN.
First I started from cleaning data in python. I had 3 csv files with different data:

- Daily sales, contains columns: date of sale, gross sale, net purchase, margin
- Monthly sales,  contains columns: month, code, category, product name, quantity sold, price of purchase, 
                                    net price of sale, gross price of sale, margin, procent of margin  etc
- Yearly rotation of products, , contains columns: code, category, product name, total quantity sold, average sold per day, left in stock

After a long and diligent data cleaning and preparing process, I exported all final dataframes as new csv files.
Then I imported clean data to Power BI and made a vizualization: 

https://shorturl.at/EJ368
1st page is representing an annual financial sales report with charts by category, month and weekday



https://shorturl.at/dksyH
2nd page has a detailed report of products sold, prices and costs, margins, stock leftovers

