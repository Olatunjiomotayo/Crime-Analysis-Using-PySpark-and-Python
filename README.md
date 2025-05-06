# Crime Analysis Using PySpark and Python

## Table of Contents

- [Project Overview](#project-overview)
- [Significance](#significance)
- [Datasets Used](#datasets-used)
- [Features and Steps](#features-and-steps)
    - [Environment Setup](#environment-setup)
    - [Data Preprocessing](#data-preprocessing)
    - [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Research Questions](#key-research-questions)
- [Technologies Used Recommendations](#technologies-used-recommendations)
- [Recommendations](#recommendations)
- [Insights and Findings](#insights-and-findings)


## Project Overview

This project performs crime data analysis using Apache Spark and Python. The dataset includes police-recorded crimes and offense codes. The goal is to process, clean, and analyze the data to identify key crime trends and patterns, which can aid law enforcement agencies, policymakers, and researchers in understanding crime dynamics and making data-driven decisions.

## Significance

- Understanding crime patterns is crucial for law enforcement and urban planning. By analyzing historical crime data, authorities can:

- Identify high-crime areas and allocate resources accordingly.

- Detect seasonal or time-based crime trends.

- Improve public safety policies through data-driven insights.

- Assist in predictive policing and crime prevention strategies.

- Leverage machine learning for predictive modeling of future crime trends.

## Datasets Used

1. Police Recorded Crime (PRC) Dataset: Contains records of reported crimes across different categories from 2013 to 2023.

2. Offense Codes Dataset: Provides descriptions and classifications for different types of offenses.


## Features and Steps

### Environment Setup:

- Installation of Java, Apache Spark, and necessary Python libraries.

![Screenshot 2025-03-11 155329](https://github.com/user-attachments/assets/11fcf5b9-50e0-4f14-a1dd-4d83c42c3625)

![Screenshot 2025-03-11 155516](https://github.com/user-attachments/assets/1627f91d-3644-48c3-8077-17411ceeb552)

- Configuration of SparkSession for distributed data processing.

![Screenshot 2025-03-11 155532](https://github.com/user-attachments/assets/e1f3529b-6bb2-4d3d-a605-b9ed1c57b76b)

### Data Preprocessing

- Cleaning the dataset
- Renaming & Standardising the data
- Handling missing/null values to ensure data integrity.
- Merging multiple data sources into a unified dataset.
- Creating Spark DataFrames and temporary SQL tables for analysis.

![Screenshot 2025-03-11 160941](https://github.com/user-attachments/assets/6dd5d204-7c3d-40d9-af00-d7e6330b2814)

![Screenshot 2025-03-11 155924](https://github.com/user-attachments/assets/6a804a7e-1f5a-4d5d-a126-63d51075c7d2)

![Screenshot 2025-03-11 160223](https://github.com/user-attachments/assets/0a5c1a14-2d64-4d1b-bd36-fd35f5d488af)

![Screenshot 2025-03-11 160258](https://github.com/user-attachments/assets/9fe28ca7-9e2a-4fde-9df3-a9394407284c)

### Exploratory Data Analysis

- Identifying the most common offenses.

- Aggregating crime counts across various dimensions (time, location, type of crime).

- Visualizing trends using Matplotlib and Seaborn.

## Key Research Questions:

### 1. What is the most frequently committed offense?

![Screenshot 2025-03-11 160420](https://github.com/user-attachments/assets/18936899-ebdc-4b25-93a7-362acd34ecbb)

### 2. Which law enforcement agencies (Force Names) have the highest number of recorded offences?

![Screenshot 2025-03-11 161245](https://github.com/user-attachments/assets/fa9a61c2-e8c6-4f11-8648-2c639c977c7f)

### 3. How does the distribution of offences vary across different financial quarters?

![Screenshot 2025-03-11 161400](https://github.com/user-attachments/assets/2eb30b4a-3325-4946-b705-3de8dfab10cd)


## Technologies Used

- Apache Spark: For large-scale distributed data processing.

- Python: Using Pandas, PySpark, Matplotlib, and Seaborn for analysis and visualization.

- SQL Queries: For data aggregation, filtering, and trend analysis.

- Machine Learning (PySpark MLlib): Predictive modeling to anticipate future crime trends.

## Recommendations

- Resource Allocation: Deploy more law enforcement personnel in high-crime areas based on identified trends.

- Public Awareness Campaigns: Educate citizens on crime-prone areas and preventive measures.

- Predictive Policing: Use data insights to anticipate and prevent future crimes.

- Policy Implementation: Governments can use the findings to introduce policies that address high-risk crime categories.

- Further Research: Conduct deeper analysis by incorporating socioeconomic and demographic factors to understand root causes.


## Insights and Findings

- The dataset highlights specific high-frequency offenses, enabling better resource distribution.

- Crime occurrences show seasonal and geographical trends, which can aid in crime prevention strategies.

- Data visualization provides insights into crime distributions, helping in policymaking and law enforcement strategies.

![image](https://github.com/user-attachments/assets/b881affb-393b-48e7-a17a-b450304497d9)

![image](https://github.com/user-attachments/assets/4012c49f-c469-4659-aefc-8084dd09c7bb)
