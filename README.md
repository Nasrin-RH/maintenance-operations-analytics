Maintenance Operations Analytics – BI Project

A simple end-to-end BI project built to analyze aircraft maintenance operations using Python, SQL, and Power BI. The project simulates maintenance data, prepares it for analysis, builds DAX measures, and visualizes insights in an interactive dashboard.

Tools Used

Python (Google Colab)

SQLite (SQL inside Python)

Power BI

DAX

Project Steps

Data Generation (Python): Created synthetic maintenance dataset and exported to CSV.

Data Cleaning: Fixed data types, recalculated cost fields, prepared final dataset.

SQL Analysis: Ran queries inside Python using SQLite.

Power BI Modeling: Loaded data, formatted model, created DAX measures.

Dashboard: Built visuals for cost, delays, maintenance hours, and task status.

Key DAX Measures
TotalCost = SUM('maintenance_operations_data'[Cost])
AvgDelay = AVERAGE('maintenance_operations_data'[DelayHours])

Dashboard Output

Includes:

Total cost analysis

Delay trends

Cost breakdown

Completed vs pending tasks

Purpose

This project demonstrates core BI skills required for roles in data analytics and MRO operations.
