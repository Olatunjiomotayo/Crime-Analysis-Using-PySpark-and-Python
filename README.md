# Crime Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Significance](#significance)
-  [Datasets Used](#datasets-used)
-  [Features & Steps](#features-&-steps)
    - [Environment Setup](#environment-setup)
    - [Data Preprocessing](#data-preprocessing)
    - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-(EDA))
- [Key Research Questions](#key-research-questions)


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


## Features & Steps

### Environment Setup: Data Preprocessing: Exploratory Data Analysis (EDA): Key Research Questions:

- Installation of Java, Apache Spark, and necessary Python libraries.

- Configuration of SparkSession for distributed data processing.

### Data Preprocessing:

- Merging multiple data sources into a unified dataset.

- Handling missing/null values to ensure data integrity.

- Creating Spark DataFrames and temporary SQL tables for analysis.

### Exploratory Data Analysis (EDA):

Identifying the most common offenses.

Aggregating crime counts across various dimensions (time, location, type of crime).

Visualizing trends using Matplotlib and Seaborn.

## Key Research Questions:

What is the most frequently committed offense?

How do crime rates fluctuate over time and across different locations?

Which areas experience the highest crime rates?

Are there any patterns in crime occurrences that suggest preventive measures?

Metrics & Key Findings

Most Common Offenses:

Theft, violence, and public order offenses are the most prevalent.

Fraud-related crimes have increased significantly in recent years.

Crime Trends Over Time:

Crime rates show seasonal variations, with peaks in certain financial quarters.

Violent crimes tend to spike in specific months, suggesting possible external influences (e.g., holidays, economic downturns).

High-Crime Areas:

Certain metropolitan areas exhibit consistently high crime rates.

Regional disparities exist in crime occurrences, necessitating tailored policy interventions.

Machine Learning & Predictive Insights:

A Linear Regression model was used to predict future crime counts.

Predictive analytics suggest increasing trends in certain crime categories, highlighting areas for proactive policing.

Technologies Used

Apache Spark: For large-scale distributed data processing.

Python: Using Pandas, PySpark, Matplotlib, and Seaborn for analysis and visualization.

SQL Queries: For data aggregation, filtering, and trend analysis.

Machine Learning (PySpark MLlib): Predictive modeling to anticipate future crime trends.

Recommendations

Resource Allocation: Deploy more law enforcement personnel in high-crime areas based on identified trends.

Public Awareness Campaigns: Educate citizens on crime-prone areas and preventive measures.

Predictive Policing: Use data insights to anticipate and prevent future crimes.

Policy Implementation: Governments can use the findings to introduce policies that address high-risk crime categories.

Further Research: Conduct deeper analysis by incorporating socioeconomic and demographic factors to understand root causes.

Installation & Setup

Clone the repository:

git clone https://github.com/your-username/crime-analysis.git
cd crime-analysis

Install dependencies:

pip install pyspark pandas scikit-learn seaborn matplotlib

Run the Jupyter Notebook:

jupyter notebook

Insights & Findings

The dataset highlights specific high-frequency offenses, enabling better resource distribution.

Crime occurrences show seasonal and geographical trends, which can aid in crime prevention strategies.

Data visualization provides insights into crime distributions, helping in policymaking and law enforcement strategies.

Predictive modeling provides future crime insights, assisting in strategic law enforcement deployment.

Contributing

Feel free to fork this repository, make improvements, and submit pull requests. Contributions related to additional datasets, predictive models, and enhanced visualizations are highly encouraged.

License

This project is licensed under the MIT License.

