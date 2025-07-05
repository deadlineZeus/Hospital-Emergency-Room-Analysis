# Hospital-Emergency-Room-Analysis
This is an end-to-end data analysis project where we take a spreadsheet full of information about a hospital emergency room and try to extract useful insights from that organized data. We have used Microsoft Excel as our primary tool.
## Project Objectives-
We begin with having the data spreadsheet undorstood first and then take a look at our KPIs that we are going to extract out of it. There are data available like 
1. How many patients are getting admitted each day
2. How much each of them had to wait to be assigned to a medical professional
3. How the satisfaction score (from 0-10) each patient gave before being released
4. What are the personal information about them and from which department they are getting refered to and many more.
## Dataset Used-
- <a href="https://github.com/deadlineZeus/Hospital-Emergency-Room-Analysis/blob/main/Hospital%20Room%20Raw%20Data.csv">Raw Dataset in CSV</a>
## Tools Used-
###1.Power Query Editor:
We first take out the raw CSV file data in our Excel and before loading, we do some transformations on the existing columns using this editor before loading the data. Apart from that we also create a calendar table to later on do some timewise analysis.
###2. Power Pivot: 
We attempt to link the newly created table with the existig transformed table and establish relationship between those tables based on common column in Power Pivot tool.
###3. Pivot Tables: 
Now we insert some pivot tables on a new worksheet based on the KPIs that we have to extract.
###4. Dashboard: 
When the pivot tables are ready to be visualised, we insert the suitbale charts to show them in a new worksheet.
###5. Slicer: 
because of the required KIPs are to be visualised timewise, we add slicer to choose years, months as well as days so as to get accurate information on one click.
6. Charts: In our project we have used bar charts, pie charts, donut charts, area charts and many more so as to give each KPI the best suitable visualization method.
7. Dynamic: We have made sure a user gets to know every necessary info by just one click and hence we have connected the slicers to various pivot tables and made it easier to find the exact data that user might want to get. The buttons are clickable and if necessary it redirects to the dedicated chart/worksheet so as to give a more detailed view of the events happening there.

## Final Dashboard-
![Final Dashboard Presentation](https://github.com/user-attachments/assets/b614c570-88e4-4ed5-99cb-86bacd8f83e3)
