# Bike-Sales

# 1. Project Overview
This project involves data cleaning, analysis using PivotTables, and the creation of a dashboard in Excel. The dataset provided includes information on individuals’ demographics, income, and vehicle ownership, 

among other variables.

# 2. Data Cleaning Steps
The following steps were performed to clean the data:

Removed Duplicates: Identified and removed any duplicate entries to ensure data accuracy.

Standardized Values:

Marital Status: Standardized values ("Married" and "Single") to ensure consistency.

Gender: Ensured uniform representation ("Male" and "Female").

Trimmed Unwanted Spaces: Used the TRIM function to remove extra spaces from text fields.

Checked Spelling: Reviewed and corrected any spelling errors in categorical fields.

Standardized Age Brackets: Added and categorized age brackets using a nested IF function to classify individuals into age groups ("Middle Age," "Old").

![Bike](https://github.com/user-attachments/assets/980da005-4450-4ce7-b59a-9d1e7e265e47)

# 3. PivotTable Analysis
PivotTable 1: Average Income by Gender and Bike Ownership

Objective: Analyze the average income of individuals based on their gender and whether they purchased a bike.

Findings:

Female:

Purchased Bike (Yes): Average income is $55,774.

Did Not Purchase Bike (No): Average income is $53,440.

Overall Average Income: $54,581.

Male:

Purchased Bike (Yes): Average income is $60,124.

Did Not Purchase Bike (No): Average income is $56,208.

Overall Average Income: $58,063.

Grand Total:

Purchased Bike (Yes): Average income is $57,963.

Did Not Purchase Bike (No): Average income is $54,875.

Overall Average Income: $56,360.

Insights:

Home owners generally have a higher average income compared to non-home owners.

Males have a higher average income than females, with the highest average income observed among home-owning males.

PivotTable 2: Count of Purchased Bike by Commute Distance

Objective: Analyze the count of individuals who purchased a bike based on their commute distance.

Findings:

0-1 Miles:

Did Not Purchase Bike (No): 166

Purchased Bike (Yes): 200

Total: 366

1-2 Miles:

Did Not Purchase Bike (No): 92

Purchased Bike (Yes): 77

Total: 169

2-5 Miles:

Did Not Purchase Bike (No): 67

Purchased Bike (Yes): 95

Total: 162

5-10 Miles:

Did Not Purchase Bike (No): 116

Purchased Bike (Yes): 76

Total: 192

More Than 10 Miles:

Did Not Purchase Bike (No): 78

Purchased Bike (Yes): 33

Total: 111

Grand Total:

Did Not Purchase Bike (No): 519

Purchased Bike (Yes): 481

Overall Total: 1000

Insights:

The highest count of bike purchases is among individuals with a commute distance of 0-1 miles, with 200 bike purchases.

The lowest count of bike purchases is among individuals with a commute distance of more than 10 miles, with only 33 bike purchases.

There is a noticeable decrease in bike purchases as the commute distance increases, suggesting that shorter commutes are more likely associated with bike ownership.

PivotTable 3: Count of Purchased Bike by Age Brackets

Objective: Analyze the count of individuals who purchased a bike based on their age bracket.

Findings:

Adolescent:

Did Not Purchase Bike (No): 71

Purchased Bike (Yes): 39

Total: 110

Middle Age:

Did Not Purchase Bike (No): 318

Purchased Bike (Yes): 383

Total: 701

Old:

Did Not Purchase Bike (No): 130

Purchased Bike (Yes): 59

Total: 189

Grand Total:

Did Not Purchase Bike (No): 519

Purchased Bike (Yes): 481

Overall Total: 1000

Insights:

The highest count of bike purchases is among individuals in the Middle Age bracket, with 383 bike purchases.

The lowest count of bike purchases is among Adolescent individuals, with 39 bike purchases.

The Middle Age bracket has the highest overall count of both bike purchases and non-purchases, indicating it is the most significant group in terms of bike ownership.

![Bike Pivot](https://github.com/user-attachments/assets/f1edccaf-8759-445b-87e7-3758ef480952)

# 4. Dashboard Creation
A dashboard was created to visually represent key insights from the data:

PivotTable 1: Average Income by Gender and Bike Ownership

Chart Type: Clustered Column Chart

Description: This chart displays the average income of individuals categorized by gender and bike ownership status. It visually compares the average income for males and females who purchased and did not 

purchase a bike, highlighting differences across these groups.

PivotTable 2: Count of Purchased Bike by Commute Distance

Chart Type: Line Chart

Description: This line chart illustrates the count of bike purchases across different commute distances. It shows trends in bike ownership relative to commute distance, allowing for easy visualization of how 

bike purchases vary with commuting distance.

PivotTable 3: Count of Purchased Bike by Age Brackets

Chart Type: Line Chart

Description: This line chart presents the count of bike purchases segmented by age brackets. It highlights trends in bike ownership among different age groups, showing variations and trends in bike purchases 

across age categories.

Slicers Added:


Marital Status: Allows users to filter the data by marital status to see how bike purchases and other metrics vary across different marital statuses.

Education: Enables filtering based on education level, providing insights into bike ownership trends related to educational background.

Region: Filters the data by geographic region, allowing users to explore variations in bike ownership and income across different regions.

Summary Statistics: Displayed key statistics and metrics for quick insights (average income, most common age bracket).

![Bike Dashboard](https://github.com/user-attachments/assets/b21d8f55-c57e-4530-a470-f96104b0d551)

# 5. Conclusion

The project effectively cleaned and analyzed the dataset, leading to valuable insights. The dashboard facilitates an interactive exploration of the data, making it easier to identify patterns and trends.

