# ✈️ Fleet Utilization Analyzer using Python & Pandas

## Overview

The **Fleet Utilization Analyzer** is a Python-based aviation data analysis project developed using **Pandas**. It automates the analysis of aircraft fleet utilization by reading operational data from a CSV file, calculating key fleet statistics, identifying the highest and lowest utilized aircraft, categorizing utilization levels, and generating an updated maintenance report.

This project simulates tasks commonly performed by **CAMO (Continuing Airworthiness Management Organization)** engineers, fleet planners, and airline maintenance planners.

---

# Features

- Read aircraft fleet data from a CSV file
- Calculate total number of aircraft
- Calculate total fleet flight hours
- Calculate average fleet utilization
- Identify the highest utilized aircraft
- Identify the lowest utilized aircraft
- Categorize aircraft utilization into:
  - HIGH
  - MEDIUM
  - LOW
- Generate an updated maintenance report
- Export processed data to a new CSV file

---

# Technologies Used

- Python 3
- Pandas
- CSV File Handling
- PyCharm

---

# Project Structure

```
Fleet-Utilization-Analyzer/
│
├── aircraft_data.csv          # Input dataset
├── fleet_utilization.py       # Main Python program
├── maintenance_report.csv     # Generated report
├── README.md
```

---

# Sample Dataset

| Aircraft | Aircraft_Type | Base | Flight_Hours | Flight_Cycles |
|-----------|--------------|------|-------------:|--------------:|
| ACE001 | Boeing 737 | New York | 12450 | 8900 |
| ACE002 | Airbus A320 | Los Angeles | 15230 | 10200 |
| ACE003 | Boeing 777 | Chicago | 28900 | 5600 |

---

# Calculations Performed

## Fleet Statistics

The program calculates:

- Total Aircraft
- Total Flight Hours
- Average Flight Hours

---

## Highest Utilization

The analyzer identifies the aircraft with the highest accumulated flight hours.

Example:

```
Highest Utilization

Aircraft : ACE007
Type      : Boeing 747
Hours     : 38200
```

---

## Lowest Utilization

The analyzer also identifies the least utilized aircraft.

Example:

```
Aircraft : ACE013
Type      : Boeing 737 MAX
Hours     : 8900
```

---

# Utilization Classification

Aircraft are categorized according to their flight hours.

| Flight Hours | Status |
|--------------|--------|
| Above High Threshold | HIGH |
| Medium Range | MEDIUM |
| Lower Range | LOW |

A new column named **utilization_status** is automatically added to the dataset.

Example:

| Aircraft | Flight_Hours | Utilization_Status |
|-----------|-------------:|-------------------|
| ACE001 | 12450 | LOW |
| ACE003 | 28900 | HIGH |
| ACE006 | 22400 | HIGH |

---

# Output Report

The processed data is exported as a new CSV file.

Example:

```
maintenance_report.csv
```

The report contains:

- Original aircraft information
- Flight hours
- Flight cycles
- Utilization status

---

# Skills Demonstrated

This project demonstrates practical knowledge of:

- Python Programming
- Pandas DataFrames
- CSV File Processing
- Data Analysis
- Conditional Logic
- Data Filtering
- Data Transformation
- Report Generation
- Aviation Fleet Analysis

---

# Future Improvements

Planned enhancements include:

- Maintenance Due Forecasting
- Remaining Flight Hours Calculation
- Remaining Flight Cycles Calculation
- Aircraft Health Dashboard
- Excel Report Generation
- Interactive Graphs
- Utilization Charts
- Maintenance Priority Classification
- User Interface using Streamlit

---

# Learning Outcomes

Through this project, I learned how to:

- Read and process CSV datasets using Pandas
- Analyze aviation operational data
- Generate automated maintenance reports
- Work with DataFrames efficiently
- Perform statistical calculations
- Export processed data
- Apply Python to real-world aviation engineering problems

---

# Future Aviation Projects

This project is part of my aviation engineering portfolio.

Upcoming projects include:

- Aircraft Maintenance Forecast Generator
- Component Life Tracking System
- Airworthiness Directive Tracker
- Maintenance Planning Dashboard
- Aircraft Maintenance Cost Analyzer
- Flight Cycle Monitoring System
- Technical Records Management System

---

# Author

**Mohammed Faraz Ahmed**

Aeronautical Engineering Student

Aspiring CAMO / Continuing Airworthiness Engineer

Focused on applying Python, Excel, and data analytics to aviation maintenance planning and fleet management.

## License

This project is intended for educational and portfolio purposes.
