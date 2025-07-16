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

## Project Workflow & Tools Used
1.	Data Source: The dataset insurance.csv contains client data with fields like age, gender, BMI, smoker status, charges, etc.
2.	Data Storage: The raw dataset was first imported into a MySQL database for structured storage.
3.	Data Transformation: Using Python (Pandas), we:
o	Cleaned and categorized the data (e.g., age groups, parent flag).
o	Converted categorical columns to numeric.
o	Computed measures like total charges, smoker percentages, etc.
o	Saved the final transformed dataset as a .csv file.
4.	Data Visualization: Using Power BI, we:
o	Connected the transformed CSV.
o	Created custom visuals, slicers, cards, and a gauge.
o	Designed an interactive dashboard reflecting client metrics.
