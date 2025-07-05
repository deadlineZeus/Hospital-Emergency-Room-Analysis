## Hospital-Emergency-Room-Analysis
This is an end-to-end data analysis project where we take a spreadsheet full of information about a hospital emergency room and try to extract useful insights from that organized data. We have used Microsoft Excel as our primary tool.

We begin with having the data spreadsheet undorstood first and then take a look at our KPIs that we are going to extract out of it. There are data available like 
1. How many patients are getting admitted each day
2. How much each of them had to wait to be assigned to a medical professional
3. How the satisfaction score (from 0-10) each patient gave before being released
4. What are the personal information about them and from which department they are getting refered to and many more.

Power Query Editor: We first take out the raw CSV file data in our Excel and before loading, we do some transformations on the existing columns using this editor before loading the data. Apart from that we also create a calendar table to later on do some timewise analysis.

Power Pivot: We attempt to link the new created table with the existig transformed table and create relationship between those tables in Power Pivot.
Pivot Tables: Now we insert some pivot tables on a new worksheet based on the KPIs that we have to extract.
Dashboard: When the pivot tables are ready to be visualised, we insert the suitbale charts to show them in a new worksheet. 
Slicer: because of the required KIPs are to be visualised timewise, we add slicer to choose years, months as well as days so as to get accurate information on one click.
Charts: In our project we have used bar charts, pie charts, donut charts, area charts and many more so as to give each KPI the best suitable visualization method.
