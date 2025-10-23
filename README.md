#  -->
I worked on an Amazon Sales dataset with over 3,000 transactions from 2011–2014. 
My goal was to clean the data, analyze key performance metrics like sales, profit, and order trends, 
and design an interactive Power BI dashboard to help management track business performance.
Include: 
• Project name: Amazon Sales Performance Dashboard 
• Tools: Excel, Power BI, DAX, Power Query 
• Key metrics: Sales, Profit, Orders, Margin

Data Cleaning 
First, I inspected the raw data for quality. I checked for missing values, duplicates, and columns with 
incorrect types. 

Next, I standardized formats and cleaned values. In Power Query I:
•	Removed special characters from numeric fields and converted to numeric.
•	Normalized text (trim, lowercase) for category and product fields.
•	Parsed and unified date formats using Change Type and Using Locale where needed.
•	Removed exact duplicate rows.
•	Split Column by Delimiter  -> Geography ->Country – City -State

