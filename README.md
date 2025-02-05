# Data-Wrangling-with-Baltimore-City-911-Report-Data

**Overview**

This project focuses on analyzing and cleaning Baltimore City's 911 emergency response dataset to extract insights and visualize crime patterns. The dataset consists of 292,761 records and 16 attributes, requiring significant data cleaning and transformation. The goal is to identify crime type variations, temporal crime patterns, and distributions across different time frames.

**Dataset**

Dataset Name: Baltimore911.csv

Source: Baltimore911 

Dataset Size: 292,761 records, 16 attributes

**Data Processing & Cleaning
**
1. Initial Exploration
Identified 16 attributes (columns) and 292,761 rows (instances).
Conducted an initial statistical summary of discrete and numerical attributes.
2. Handling Missing Data
Location 1 attribute had 100% missing values and was dropped.
Rows with missing values in other attributes were removed.
After cleaning, the dataset was reduced to 258,723 records for better analysis.

**Analysis & Insights
**
1. Crime Type Variation Analysis
Larceny is the most frequently occurring crime.
Arson is the least frequent crime type in the dataset.
2. Temporal Pattern Analysis
Year-to-Year Crime Type Distribution: Trends in crime types over different years.
Month-to-Month Crime Distribution: Identifies seasonal variations in crime.
Day-of-Week Crime Type Distribution:
Crime types mapped across Monday to Sunday (0-6 on x-axis).
Larceny is most common, peaking on Fridays.


**Dashboard Creation
**
1. Static Dashboard
Visualizes all crime types with frequency using different colors.
Helps in quick pattern identification across different crime types.
2. Dynamic Dashboard
Enables user interaction to adjust parameters and observe crime pattern changes dynamically.
Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)
SQL (for data querying and filtering)
Tableau (for static and dynamic dashboard creation)
Project Structure

**Baltimore-911-Data-Wrangling/**
├── data/                # Raw and cleaned dataset files
├── notebooks/           # Jupyter Notebooks for data cleaning & analysis
├── scripts/             # Python scripts for data wrangling and visualization
├── dashboard/           # Tableau dashboards and reports
├── README.md            # Project documentation (this file)

**Results & Observations**

Data cleaning reduced the dataset by ~12% but improved analysis accuracy.
Crime patterns exhibit a strong weekly and monthly variation.
Fridays show the highest crime rate, especially for Larceny.
Dashboard visualizations effectively highlight crime trends and frequencies.


**Future Enhancements
**
Incorporate machine learning models to predict crime hotspots.
Extend dashboard capabilities for real-time data analysis.
Use geospatial analysis for location-based crime pattern detection.

**Contributions**

Contributions are welcome! Feel free to fork this repository and submit pull requests.

