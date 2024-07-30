# Adventure Works Sales-Dashboard

## Problem Statement
This Power BI project, titled Adventure Works, aims to provide insights and analysis on key business metrics. The dashboard includes several visualizations to track KPIs, compare regional performance, analyze product-level trends, and identify high-value customers.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Errors and empty values are identified and eliminated and all the data are ensured with quality and precision of data types were also checked.
- Step 5 : Data was loaded into the front end of power bi.
- Step 6 : Done data modelling in the model view, by identifiying fact and dimention's table, containing both star and snowflake schema's.
- Step 7 : Arranged the tables in such a way that the flow of data is from top to bottom.
- Step 8 : Created the Measure grouping and addded the entire measures created in one place to avoid the confusion.
- Step 9 : Created calculated columns for row by row calculations whereever reqiured.
- Step 10 : The Executive dashboard Page -  highlights crucial Key Performance Indicators (KPIs) such as Monthly sales Revenue, Orders and Returns. Used cluster bar chart for identifying Orders by different product Category.
	    This helps in monitoring business health and operational efficiency.
- Step 11 : In the Map dashboard Page -  we are Comparing Regional Performance. The regional analysis component of the dashboard allows for the comparison of different geographic areas. 
            It helps in understanding which regions are performing well and which ones require more attention.
- Step 12 : In Product Detail Page - Detailed analysis of product-level data enables the identification of trends in product sales and Target and added the area chart for analysing profit and return trending.
            Kept this page as drill through from the Excutive dashboard from the specific product selected.
- Step 13 : In Customer Details Page - This page includes a section dedicated to identifying high-value customers through top N filters based and text cards and used the Pie-charts for identifying the Orders categorized by Income level
            and Occupation. 

