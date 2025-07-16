# TSafe Insurance - Analytical Dashboard for Insurance Data
## Project Objective
To analyze and visualize health insurance data in order to uncover insights about customer demographics, policy costs, and health habits. This project demonstrates an end-to-end simple data pipeline, transformation using Python, storage in MySQL, and interactive visualizations using Power BI.

## Data Used
- <a href="https://github.com/BillJoshuaS/Data-Engineering/blob/main/insurance.csv">Raw Dataset</a>
- <a href="https://github.com/BillJoshuaS/Data-Engineering/blob/main/insure_lvl1_transformed.csv">Transformed Dataset</a>

## Key Questions Answered (KPIs)
-	What is the average BMI across different age categories?
-	How do smoking habits impact insurance charges?
-	What are the total charges per client category (based on age)?
-	How are charges distributed across US regions and parenthood status?
-	What percentage of the clients are smokers or parents?
-	What is the total and average policy charge amount?

- Dashboard Interaction <a href="https://github.com/BillJoshuaS/Data-Engineering/blob/main/InsuranceBoard_lvl1.pbix">View Dashboard</a>

## Project Workflow and Process
-	Imported the insurance.csv dataset containing client data into a MySQL database for structured storage.
-	Transformed the data using Python (Pandas): cleaned, categorized age groups, created parent flag, encoded categories, and calculated key metrics.
-	Saved the transformed dataset as a CSV file for further use.
-	Loaded the CSV into Power BI to build an interactive dashboard.
-	Designed visuals including clustered charts, slicers, cards, and gauges to display insights like BMI, smoker impact, age categories, and regional distributions.

## Dashboard
<img width="1322" height="742" alt="PBI_Dashboard" src="https://github.com/user-attachments/assets/1f54aaad-1435-4b0e-85fa-6a4f1988dcdf" />

