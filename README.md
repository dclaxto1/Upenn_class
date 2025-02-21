# Upenn_class          
    
Used conditional formatting to fill each cell in the outcome column with a different color, depending on whether or not the associated campaign was successful, failed, canceled, or was currently live.
 
Created a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
Used conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The starts at 0 with a dark shade of red, and transitions to green at 100 and blue at 200.

Created a new column called Average Donation that uses a formula to find how much each project backer paid on average.

Created two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.

Created a stacked-column pivot chart that can be filtered by country based on the table that you created.

Created a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

Created a stacked-column pivot chart that can be filtered by country and parent category based on the table that I created.

Created a new column named Date Created Conversion that will use this formulaLinks to an external site. to convert the data contained in launched_at into Excel's date format.

Created a new column named Date Ended Conversion that will use this formulaLinks to an external site. to convert the data contained in deadline into Excel's date format.

Created a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.

Created a report in Microsoft Word, and answer the following questions:
1. Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
2. What are some limitations of this dataset?
3. What are some other possible tables and/or graphs that we could create, and what additional value would they provide?

Using the COUNTIFS() formula, I counted how many successful, failed, and canceled projects were created with goals within the ranges listed above. I then populated the Number Successful, Number Failed, and Number Canceled columns with these data points.
 
I added up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, found the percentage of projects that were successful, failed, or canceled per goal range.

Created a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.

Created a new worksheet in your workbook, and create one column for the number of backers of successful campaigns and one column for unsuccessful campaigns.

Used Excel to evaluate the following values for successful campaigns, and then did the same for unsuccessful campaigns:
1. The mean number of backers.
2. The median number of backers.
3. The minimum number of backers.
4. The maximum number of backers.
5. The variance of the number of backers.
6. The standard deviation of the number of backers.



