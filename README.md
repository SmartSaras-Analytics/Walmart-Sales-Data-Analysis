# Walmart-Sales-Data-Analysis
About:

We are analysing Walmart's sales data to identify high-performing branches and products, analyze the sales patterns of various products, and understand customer behavior. The primary objective is to enhance and optimize sales strategies. The dataset utilized in this project is sourced from the Kaggle Walmart Sales Forecasting Competition.

Analysis List:

Product Analysis

Perform an analysis on the data to gain insights into different product lines, determine the top-performing product lines, and identify areas for improvement in other product lines.

Sales Analysis

The objective of this analysis is to address the inquiry regarding the sales trends of the product. The outcomes of this analysis can assist in evaluating the efficiency of each applied sales strategy in the business and determining necessary modifications to increase sales.

Customer Analysis

This analysis is focused on identifying various customer segments, understanding purchasing trends, and evaluating the profitability associated with each of these customer segments.

Approach Used

1. Data Wrangling:
During this initial phase, the data is examined to detect any NULL or missing values, and strategies for data replacement are implemented to address and substitute these values effectively.
  Build a database
  Create a table and insert the data.
  Select columns with null values in them. Null values are not present in our database because, in creating the tables, NOT NULL was specified for each field, effectively filtering out any null values.

3. Feature Engineering:
This will help use generate some new columns from existing ones.

  Add a new column named time_of_day to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.
  
  Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.
  
  Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.
  
  
3. Exploratory Data Analysis (EDA):

Conducting exploratory data analysis is essential to address the project's listed questions and objectives.

Business Questions to Answer:

1.How many unique cities does the data have?

2.In which city is each branch? 

3.How many unique product lines does the data have?

4.What is the most selling product line? 

5.What is the total revenue by month?

6.What month had the largest COGS?

7.What product line had the largest revenue? 

8.What is the city with the largest revenue? 

9.Which city has the largest tax percent/ VAT (Value Added Tax)? 

10.Which customer type buys the most?



