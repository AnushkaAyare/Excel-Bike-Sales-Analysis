# Excel Data Analysis Project: Bike Sales Customer Segmentation

## Project Overview
This project involves a comprehensive customer segmentation and sales analysis using advanced Excel features. The goal was to identify key demographics that correlate with bike purchasing behavior to provide targeted recommendations for marketing and inventory management.

## Dataset
* **Source:** Fictional company bike sales data (Includes customer demographics, income, location, and purchase history).
* **Data in Repository:** The Excel files containing the cleaned data, pivot tables, and final dashboard are attached.

## Key Analysis & Techniques Used

### 1. Data Cleaning and Preparation
* **Data Standardization:** Used **`IF` statements** and **`VLOOKUP`/`INDEX MATCH`** to standardize demographic data and create new segmentation columns (e.g., creating an "Age Bracket" column from raw `Age` data).
* **Naming Conventions:** Ensured all columns and table ranges were properly named for easy referencing in formulas and Pivot Tables.

### 2. Pivot Table Aggregation
* Created multiple **Pivot Tables** to summarize key metrics and find correlations, including:
    * Income vs. Bike Purchase Rate
    * Commute Distance vs. Bike Purchase Rate
    * Gender and Marital Status vs. Average Income
    * Education Level vs. Purchasing Decision
* These pivot tables serve as the backbone for the final dashboard visualizations.

### 3. Dashboard Design and Interactivity
* **Visualization:** Built a single, consolidated dashboard using various chart types (bar charts, pie charts, column charts) sourced directly from the pivot tables.
* **Interactivity:** Implemented **Slicers** to allow users to dynamically filter all charts based on key dimensions (e.g., Region, Education, Occupation). This gives the user an interactive experience, simulating a dynamic BI tool.
* **Key Findings Display:** Clearly highlighted the main insights found during the analysis directly on the dashboard (e.g., "Customers with higher income and partial college education are the most likely buyers").

## Tech Stack
* **Microsoft Excel:** Primary tool for all data cleaning, analysis, and visualization.
* **Key Formulas/Features Used:** Pivot Tables, Slicers, `VLOOKUP`, `INDEX MATCH`, `IF` Statements, Named Ranges, Conditional Formatting.

