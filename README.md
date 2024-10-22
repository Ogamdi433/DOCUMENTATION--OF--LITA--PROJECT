# DOCUMENTATION_OF_LITA_PROJECT

### project title: Salary disparities across Companies: "An In-Dept Analysis of compensation Trends"

This analysis project aims at outlining the company's activity and the impact it has brought to the organisation over a specific time. The details can vary, but typically include metrics about leads, highest performing company, revenue generated, and overall Company's performance. this will give us insight about the lows and highs of the company's performance and how improvement can be made on the staff salary to increase their current percentage 

### Data sources
the primary sources of data used for this project are;  sales records, customer feedback, and operational metrics. with some external sources such as market research reports and the industry benchmarks.

### Tools used
- Microsoft Excel [download here](https://www.microsoft.com)  and Power Bi. [download here](https:www.powerbi.microsoft.com/en-us/desktop).
  1.  for Data cleaning
  2.  for Analysis
- PivotCharts for data Visualization
- Github for portfolio building
  
  ### Data cleaning
  data cleaning involves several processes. to ensure data accuracy, completeness and consistency, here is a step-by-step process.
- handling missing files
  1. identify missing values (e.g, NULL, blank, NA).
  2. decide on replacement stategies (e.g,  mean, median, imputation).
  3. replace missing values
- data normalization
  1. standardize date formats
  2. convert categorical variables into numerical variables
- error detection and correction
  1. identify errors
  2. correct errors manually or using algorithms
  3. verify corrections
- data transformation
  1. aggregate data (e.g, group by, pivot)
  2. merge datasets
  3. transpose data
-data validation

### Exploratory data analysis (EDA)
EDA involves examining and summarizing data to understand patterns, trends and corrections. here is a comprehensive EDA checklist.
 -  what are the top-selling products/category
 -  which regions/territories generate most most sales
 -  how do sales vary by season/holiday
 -  which customer segments drive most sales
 -  what marketing channels are most effective

### Data analysis
As a data analyst, the first thing that should be in mind after importing your data is to clean the data, prepare the data and summarize the data.
this is where we do an explicit explanation of our data.
in preparation of data, 
- you import data
- clean and format data. i.e removing duplicates, handling missing files etc.
- and finally, organise your data into tables or pivot tables.

 The table below shows my data cleaning using power Bi with all the applied steps used.
 
  
  ![power bi data cleaning](https://github.com/user-attachments/assets/eee3b840-6865-484e-8097-980fe861d267)

  Using Excel functions such as SUM, AVERAGE, COUNTA, MAX, MIN, LARGE AND SMALL funtions to summarise my data.
  below is the table summarised.

  
  ![summary using excel functions](https://github.com/user-attachments/assets/bcd96cf3-b426-4699-96b6-f1167e26940a)

     Hence, with Microsoft Excel i was able to summarize my data by calculating the;
  - GRAND TOTAL of the staff salary
  - AVERAGE salary
  - HIGHEST alary
  - LOWEST salary
  - TOTAL number of staff
  - FOURTH highest salary
  - THIRD lowest salary.

     According to my table above, the fuctions for the above mentioned problems are;

     GRAND TOTAL =SUM(D8:D27)
    AVAERAGE =AVERAGE(D8:D27)
    HIGHEST =MAX(D8:D27)
    LOWEST =MIN(D8:D27)
    TOTAL STAFF =COUNTA(B8:B27)
    FOURTH HIGHEST =LARGE(D8:D27,4)
    THIRD LOWEST  =SMALL(D8:D27,3).
       
    In conclusion, the formula varies according to the combination of your column and rows.
    however, my analysis revealed;
    1. the highest salary earners
    2. the lowest salary earners
    3. the top 4 and bottom 3 salary earners
    4. and the total no of staff.


    ### Data Visualization
    This is the process of creating graphical representation of data to better understand, analize and communicate insights. it helps transform complex data into intuitive, interactive and visually appealing formats.. it also simplifies complex data and enhances decision making.
    below graphs shows the visualization of all my data.

    
![pivot chart](https://github.com/user-attachments/assets/c3bda84c-17ce-44d1-adad-81614de28d4a)


the chart above shows 5 companies with the lowest salary, explaining it in the ascending order.


![pie chat](https://github.com/user-attachments/assets/6f1bffa8-77a4-480b-a376-b999356495ce)

this is a pie chart showing 10 companies with the highest salary, explaining it in the ascending order.


![pie chart 2](https://github.com/user-attachments/assets/9f5635d6-0d29-41f4-9e30-1fc235c2ee9b)

This chart above shows the total number of all the staff in the company with their salary percentage.

In conclusion data visualization ensures clarity, simplicity annd accessibility.
In all, my analysis reveals significant salary disparities across the companies with variations driven by location and company size.
by this analysis the company will be able to avoid future loss by;

- enhancing talent attraction and retention.
- foster fairer compensation practices. and
- improve employee satisfaction.
