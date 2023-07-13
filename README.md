# Excel Project - Bikes Sales
## Introduction

Hello and welcome to my Excel Project. This won't be a deep dive like my Google Data Analytics Case Study, but rather a quick showcase of my Data Analytics skills focusing on Excel.  

If you're interested in the final product or wanted to test things out for yourself, I have put the dataset linked at the bottom of the README.



## Data Sources

The Dataset used in this project was retrieved from the [github](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx) of Alex the Analyst, a Youtuber who specializes in educational videos for Data Analytics.



## Changelog & Cleaning

Below I describe, step-by-step the data cleaning and manipulation I performed to the dataset.  I created a few new sheets in order to have a sheet to manipulate the data without disrupting the original, a sheet for my pivot tables and a sheet for my visualizations turned into a dashboard with filters. 

**Bike Sales**  
  1. Added three new sheets, "Working Sheet", "Pivot Table", and "Dashboard".
  2. Copied all data to "Working Sheet".
  3. Used filters and conditional formatting to check for duplicates, blanks, spelling mistakes, etc.
  4. Checked the ID value lengths with =len.
  5. Used Find and Replace to change some data to make more sense when manipulating the data (changed m and s to married and single under Marital Status column and f and m to female and male under the gender column).
  6. Changed 10+ miles to More than 10 miles to make a future visualization easier to use.
  7. Added a new column Age Bracket and then entered the following nested formula referencing the Age column: =IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid"))).
  8. Created 4 pivot tables in the "Pivot Table" sheet using the data from "Working Sheet".  The pivot tables were for the average income of the customers by gender, the customer age bracket compared to whether or not they purchased bikes, commute distance compared to whether or not they purchased a     bike and one for specific ages.
  9. Created visualizations for the first three pivot tables referenced above.
  10. Copied the visualizations to the "Dashboard" sheet.
  11. Cleaned up the dashboard, created slicer filters and connected the filters to all three visualizations



## Dataset
You can find the Excel dataset to check everything out for yourself here: [Bikes Sales Excel Project](https://github.com/stgordillo/bike_sales_excel_project/files/12035103/Bikes.Sales.Excel.Project.xlsx)
