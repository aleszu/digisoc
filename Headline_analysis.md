
# Headline analysis for JRNL 3610

## Load CSV of content analytics into Google Sheets

Format all dates to 6/5/2017 using Format -> Number -> Date

## Visualize amount of coverage across time

Select and highlight "date" and "headline" and create a chart using Insert -> Chart...

Select column chart

Select "Aggregate column A" 

Do you see any periodic dips? To what can you attribute that?

![image](http://aleszu.com/classes/digisoc/headlines1.png)

## Count the most prolific writers

Create a pivot table using Data -> Pivot table...

In Rows, click Add field and select "author"

In Values, click Add field and select "author" and then select "Summarize by COUNTA" which counts up the number of values in the "author" column.

Copy the resulting pivot table and paste into a new sheet, naming your columns "author" and "articles"

Click Data -> Turn on filter. Sort the data by most prolific writer. Clean up a table of the top 10 or top 20 writers.

![image](http://aleszu.com/classes/digisoc/table.png)

## Visualize the most prolific writers

Select column "author" 

Create a chart using Insert -> Chart...

![image](http://aleszu.com/classes/digisoc/authors.png)

## Visualize headline length

Add a column and name it "headline_length" 

Add the following formula into the second row of this new column "=len(B2)" where B2 is the location of the first headline. 

Apply this formula to the entire column by double-clicking the bottom-right of the first cell into which you've pasted the formula.

Select the column and create a chart using Insert -> Chart...

Select "Histogram chart" 

![image](http://aleszu.com/classes/digisoc/headlines2.png)











