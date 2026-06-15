# Hospitality Analysis EDA Project
---
# AtliQ Hotels Data Analysis Project

## Project Overview

This project focuses on analyzing hotel booking data for AtliQ Hotels using Python and Pandas. The objective is to clean, transform, and analyze booking data to uncover business insights related to occupancy, revenue, customer ratings, room performance, and booking trends.

The project follows a complete data analytics workflow including data exploration, data cleaning, data transformation, and insight generation.

---

## Dataset

The analysis uses multiple datasets:

* dim_date.csv
* dim_hotels.csv
* dim_rooms.csv
* fact_aggregated_bookings.csv
* fact_bookings.csv

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Project Workflow

### 1. Data Exploration

* Loaded and explored multiple datasets
* Examined data structure and distributions
* Analyzed booking platforms and room categories
* Investigated hotel and city-level information

### 2. Data Cleaning

Performed several data quality checks and corrections:

* Removed invalid guest records
* Detected and removed revenue outliers using statistical methods
* Identified missing values
* Replaced null values in capacity using the median
* Filtered records where successful bookings exceeded room capacity

### 3. Data Transformation

* Created Occupancy Percentage (`occ_pct`) metric
* Converted occupancy values into percentage format
* Merged multiple datasets for comprehensive analysis
* Prepared data for business intelligence reporting

---

## Business Questions Answered

### Occupancy Analysis

* What is the average occupancy rate for each room category?
* Which room categories perform best?
* What is the average occupancy rate across cities?
* Is occupancy higher on weekdays or weekends?
* What was the occupancy rate for different cities during June?

### Revenue Analysis

* What is the total revenue realized by city?
* What is the month-wise revenue trend?
* Which hotel properties generate the highest revenue?
* What is the revenue contribution by booking platform?

### Customer Analysis

* What is the average customer rating across cities?
* How do customer ratings vary by location?

---

## Key Data Processing Techniques

* Data Cleaning
* Outlier Detection
* Missing Value Handling
* Feature Engineering
* Data Transformation
* Dataset Merging
* GroupBy Aggregations
* Business KPI Analysis

---

## Key Insights

* Occupancy trends vary across room categories and cities.
* Weekend occupancy is generally higher than weekday occupancy.
* Revenue generation differs significantly by city and hotel property.
* Booking platforms contribute differently to overall revenue.
* Customer ratings provide insights into location-wise performance.

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Exploratory Data Analysis (EDA)
* Data Cleaning and Preprocessing
* Handling Missing Values and Outliers
* Data Transformation and Feature Engineering
* Merging and Integrating Multiple Datasets
* Business Intelligence and KPI Analysis
* Generating Actionable Insights from Real-World Data

---

## Future Improvements

* Build an interactive dashboard using Power BI or Tableau
* Develop revenue forecasting models
* Predict occupancy rates using Machine Learning
* Create automated reporting workflows

---

## Author

Jashini Mallidi

Aspiring AI Researcher | Data Science & Machine Learning Enthusiast
