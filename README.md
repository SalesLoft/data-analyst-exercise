# SalesLoft Data Analyst Exercise

Welcome to the SalesLoft Data Analyst offline exercise. This is a chance for you to show us your grasp of crucial skills which play a key role in the day-to-day of a Data Analyst at SalesLoft. If you feel that there are any questions that are unclear, please let us know. 

The exercise consists of three parts. 

1. A SQL Challenge
2. A Visualization Component
3. A Bonus Exploratory Problem

## Overall Instructions
Test
## Submisson

## SQL Challenge

A few things to note before you get started:

* Please do all work for this portion of the exercise in SQL. While R or Python are useful tools, its important that you can use SQL to achieve the correct result. Any variant of SQL is fine but Postgres is preferred. 
* There are blank/null values in the  data set and it reflects the nature of real world data.
* The questions in this portion of the exercise are strictly to demonstrate SQL knowledge, so please take their intent with a grain of salt.
* Use of documentation, online resources, or StackOverflow is _encouraged_. 

### Instructions

* Create a SQL database using the included [CSV files](/sql_challenge/data)
* Use the database created to answer all the questions.
* Provide all code you used to answer questions, set up the db, and import data in the [SQL Directory](/sql_challenge/sql)
* Leave comments where you feel clarity is needed. 

### Questions

1. Data Integrity & Cleanup

    Alphabetically list all the country codes in the continent map table that appear more than once. For countries with no country code make them display as "N/A" and display them first in the list. 

2. List the Top 10 Countries by year over year % GDP per capita growth between 2011 & 2012. 

    % year over year growth is defined as `(GDP Per Capita in 2012  -  GDP Per Capita in 2011)  /  (GDP Per Capita in 2011)`

    The final product should include columns for:
    - Rank
    - Country Name
    - Country Code
    - Continent
    - Growth Percent

3. For the year 2012, compare the percentage share of GDP Per Capita for the following regions: North America (NA), Europe (EU), and the Rest of the World. Your result should look something like:

    North America  | Europe | Rest of the World 
    ------ | ------ | -------------
    X%  | Y%  | Z%

4. For years 2004 through 2012, calculate the average GDP Per Capita for every continent for every year. The average in this case is defined as the `Sum of GDP Per Capita for All Countries in the Continent / Number of Countries in the Continent`

    The final product should include columns for:
    - Year
    - Continent
    - Average GDP Per Capita

5. For years 2004 through 2012, calculate the median GDP Per Capita for every continent for every year. The median in this  case is defined as `The value at which half of the samples for a continent are higher and half are lower`

    The final product should include columns for:
    - Year
    - Continent
    - Median GDP Per Capita


## Visualization Challenge

This portion of the exercise is aimed at understanding how you would convey the results of your work to stakeholders. There's no right or wrong choice for this part.

You can do this portion of the exercise in any tool you'd like. Excel, Google Sheets, Google Data Studio, even notebook software like Jupyter will work.


### Instructions
- Visualize the results of the questions 3, 4 & 5 from the SQL exercise. 
- If you're doing your work in excel or google sheets, please clearly label your data sets and provide the resulting file in the [Viz Challenge](/viz_challenge) directory.
- If you're doing your work in a cloud based visualization tool or other BI software that is publicly accessible, provide a link to the visualizations in a  file in the [Viz Challenge](/viz_challenge) directory.
- If you're doing your work in a visualization tool or other BI software that _isn't_ publicly accessible, provide an artifact that contains the visualizations in the [Viz Challenge](/viz_challenge) directory.
- If you're doing your work in a notebook software, provide the resulting file and instructions on how to run  it in the [Viz Challenge](/viz_challenge) directory.



## Exploratory Problem



