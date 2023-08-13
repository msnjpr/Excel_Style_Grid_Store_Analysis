**Objective**

Style Grid Store is a clothing store who wants to create an annual sales report for 2022. So that, Style Grid Store can understand their customers
and grow more sales in 2023

I have done Data Cleaning, Data Processing, Data Analyzing & Created Dynamic & Interactive Dashboard


Data Cleaning

I checked column by column if all the data is correct and looks good like no null values, All Order id are in numbers etc..

There was discrepancy in Gender column where some places for Men it was written as Male or some place it was M.
Same way for Women also it was written as Women or some where W only. To fix this i used Find & Replace in Excel after that we have only two types of Category left Men & Women

Also Quantity data was not in correct Format some written in Alphabets. So changed it to Numbers by Find & Replace


Data Processing

I did some calculation that helps in analyzing the data

There is a relationship between Gender and Age but it is difficult to show each Age with Gender. So I have created a new column Age Group and divided the Age into 3 Groups.
For this i have used IF Else condition = =IF(E2>=50,"Senior", IF(E2>=30,"Adult", "Teenager"))


Also Create a new column Month and take out month from the already existing column date by using Text formula 


Data Analysis

I have a created the following Pivot tables to analyse the data

1. Sale vs Order     -  Created a pivot table and put Sum of Amount and Count of Order ID in values and Month under rows and use Combo chart to visualize
2. Man vs Women      -  Created a pivot table and put Gender in Rows & Sum of Amount in values and use Pie chart to visualize
3. Order Status      -  Created a pivot table and put Status in Rows & Count of Order ID in values and use Pie chart to visualize
4. Top 5 Sales State -  Created a pivot table and put ship-state in Rows & Sum of Amount in values and then use filter top 5 state and use Horizontal Bar chart to visualize
5. Age & Gender      -  Created a pivot table and put Age Group in Rows & Gender in columns and count of Order Id in Values then i used show Value as % of Grand Total and use 
                        column chart to visualize
6. Channels          -  Created a pivot table and put Channels in Rows & Count of Order ID in values then i used show Value as % of Grand Total and use 
                        Pie chart to visualize

Dynamic & Interactive Dashboard

To make Pivot Charts dhynamic i have inserted 3 Slicers Month, Channels & Category and connected to all the charts


Insights

1. Adule age group (30-49 yrs) is max contributing (50%)
2. Women are more likely to buy compared to men (65%)
3. Maharashtra, Karnataka and Uttar Pradesh are the top 3 states
4. Amazon, Flipkart and Myntra channels are max contributing (80%)


**Final Conclusion to improve Style Grid Store**

Target women customers of age group (30-49 yrs) living in Maharashtra, Karnataka and Uttar Pradesh by showing ads/Copons/Offers available on Amazon, Flipkart and Myntra
