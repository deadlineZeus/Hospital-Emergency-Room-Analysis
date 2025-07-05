# Hospital-Emergency-Room-Analysis
This is an end-to-end data analysis project where we take a spreadsheet full of information about a hospital emergency room and try to extract useful insights from that organized data. We have used Microsoft Excel as our primary tool.
## Project Objectives-
The objective of this project is to summarize and visualize the Emergency Room data in 2023-2024 and understand the patient's feedback based on key service parameters that the emergency room has provided. This is to improve the service and have more potential patients as customers of the business.

## KPIs (Business Questions to be answered)-
We begin with having the data spreadsheet undorstood first and then take a look at our KPIs that we are going to extract out of it. There are insights to be extracted like
1. Daily monitoring the number of patients getting admitted to the emergency room
2. The average waiting time for patients to be assigned a medical professional after getting admitted
3. The average satisfaction score that patients are giving to the service before leaving
4. Grouping of the patients on the basis of age
5. Analyzing the medical departments which are getting referred to the patients and tracking their numbers
6. Monitoring how many patients are getting assigned within a 30 minutes time and how many cases have that time delayed
7. Gender wise anaysis
8. Percentage of patients getting medical staff associated within time and not within time 
## Dataset Used-
- <a href="https://github.com/deadlineZeus/Hospital-Emergency-Room-Analysis/blob/main/Hospital%20Room%20Raw%20Data.csv">Raw Dataset in CSV</a>
## Features & Tools Used-

1. Power Query Editor: We first take out the raw CSV file data in our Excel and before loading, we do some transformations on the existing columns using this editor before loading the data. Apart from that we also create a calendar table to later on do some timewise analysis.

2. Power Pivot: We attempt to link the newly created table with the existig transformed table and establish relationship between those tables based on common column in Power Pivot tool.

3. Pivot Tables: Now we insert some pivot tables on a new worksheet based on the KPIs that we must extract.


4. Dashboard: When the pivot tables are ready to be visualised, we insert the suitable charts to show them in a new worksheet.

5. Slicer: Because of the required KIPs are to be visualised timewise, we add slicer to choose years, months as well as days so as to get accurate information on one click.

6. Charts: In our project we have used bar charts, pie charts, donut charts, area charts and many more so as to give each KPI the best suitable visualization method.

7. Dynamic: We have made sure a user gets to know every necessary info by just one click and hence we have connected the slicers to various pivot tables and made it easier to find the exact data that user might want to get. The buttons are clickable and if necessary it redirects to the dedicated chart/worksheet so as to give a more detailed view of the events happening there.


## Final Dashboard-
![Final Dashboard Presentation](https://github.com/user-attachments/assets/b614c570-88e4-4ed5-99cb-86bacd8f83e3)
