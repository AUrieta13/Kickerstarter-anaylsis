# An Analysis of Kickstarter Campaigns

## Overview of Project 
Performing analysis on Kickstarter data from different countries and previous years to help Louise visualize campaign outcomes in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Deliverable 1
-To create the "Year" column in the Kickstarter sheet, I used this link, [Year Function](https://support.office.com/en-us/article/year-function-c64f017a-1354-490d-981f-578e8ec8d3b9), to help me get the years function for each "Data Created Conversion" provided in the sheet. ![year function](https://user-images.githubusercontent.com/90146132/138387837-59fbaaae-35f0-4a21-b6a8-79d7e33e0332.PNG).
-The Pivot Table created had the columns, rows, values, filters correctly populated so this line chart would be created correctly and saved as an image.png ![pivot table and chart](https://user-images.githubusercontent.com/90146132/138387810-99d01672-471d-41f6-aa73-22592758e8d5.PNG).
-When creating the Outcomes Based on Launch Date Chart, there were no challenges encoutered. Some possible challenges that other users may encounter when creating this chart are inputing the funtion YEAR() correctly into the the "Years" column making sure that the "Date Created Conversion" column information was interpreted correctly to properly get the year in the "Years" column. When creating the pivot chart, it would be advised to input the pivot table fields into the correct fields to get the correct chart and make sure that correct filter is applied.

### Deliverable 2
-After inserting the appropriate coulmns to hold data and dollar-amount ranges based on goals amounts, to use the function COUNTIFS() correctly to populate number of successful, failed, and canceled columns, I refered to this link [COUNTIFS_function](https://support.office.com/en-us/article/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842). This is what my formula looked like, ![COUNTIFS_formula](https://user-images.githubusercontent.com/90146132/138389274-5e1efd1f-6ca4-4d6f-8bee-d476d8fe374c.PNG).
-To get the "Total Projects" column, this is what my formula looked liked ![SUM_function_totalprojects](https://user-images.githubusercontent.com/90146132/138389483-1e9fa19f-1e39-4d98-9e26-61137c20ec54.PNG).
-After creating the "Total Projects" column, I calculated the percentage of the projects for each row using this formula ![Percentage_projects](https://user-images.githubusercontent.com/90146132/138389870-79eea5b3-c905-4683-b91e-f05d9ecf89ab.PNG).
-After all the information was inputted into the sheet, I created the line chart making sure that x-axis and y-axis were set correctly for my chart to look like this, ![outcomes_vs_goals_line_chart_axis_settings](https://user-images.githubusercontent.com/90146132/138390409-04eaf0d5-3efe-4ee5-b9f7-319ea59d620c.PNG).
-One challenge I did have when creating the Percentage columns, is that after creating the formula, I had to go to the Home tab on Excel and change the setting from "General" to  "Percentage" in the "Numbers" section of the ribbon in order to actually get the percent value. ![general_to_percentage_value](https://user-images.githubusercontent.com/90146132/138391459-37820f6e-188c-47cf-9beb-d28caa5b6f1e.PNG).

## Results

### What are two conclusions you can drew about the Theater Outcomes by Launch Date?
-Based on the line chart, we can conclude that the failed outcomes are very consistent throughout the years, but it is highest in the month of failed outcomes were in May.
-Although May was the month with the highest failed outcomes, we can conclude that it also had the highest successful outcomes from the grand total of 166 campaigns created in the month of May.

### What can you conclude about the Outcomes based on Goals?
-Based on all goal ranges created, we can conclude that the goal range that was the most successful number was the less than 1000 goal range since this was probably the most attainable goal to be met first before an other goal range set.

### What are some limitations of this dataset?
-Some limitations of this dataset include it generalizing outcomes of each goal range and not being able to accurately conclude the specific value or values of the goals in the dataset that are the successful or failed goals met. Another limitation would be figuring out what numerical values for the goal range greater than 50000 were successful and failed. It would also limit finding which country was the one with the most successful and/or goal range and theater outcomes by launch date.

### What are some other possible tables and/or graphs that we could create?
-Other possible tables we could create a pivot table with the theater outcomes based on launch date for a specific country and creating a chart to display were month was the most successful in that specific country. We could also create these tables for each country's outcomes based on goal, to figure out which country tends to have goal ranges on the higher side rather than lower and which are more successful. 


