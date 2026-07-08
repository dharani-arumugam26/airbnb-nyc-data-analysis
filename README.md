# Airbnb NYC Dataset – End-to-End Data Analysis

An end-to-end data analysis project on the Airbnb NYC dataset using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. This project covers the complete data analysis workflow, including **data understanding**, **data cleaning**, **exploratory data analysis (EDA)**, and **business insights** to uncover meaningful patterns in Airbnb listings across New York City.

---

## Project Overview

This project performs a comprehensive analysis of the **Airbnb NYC dataset** to understand the characteristics of Airbnb listings across New York City. The analysis follows a structured workflow beginning with **data understanding and quality assessment**, followed by **data cleaning**, and finally **exploratory data analysis (EDA)** to identify trends, relationships, and actionable business insights.

The primary objective of this project is to transform raw Airbnb listing data into meaningful insights that can help hosts optimize pricing strategies, assist travelers in making informed accommodation choices, and provide a better understanding of the Airbnb marketplace in New York City.

---

## Dataset Information

- **Dataset:** Airbnb NYC Open Data
- **Domain:** Hospitality / Short-Term Rentals
- **Records:** 48,895 Airbnb listings
- **Features:** 16 columns
- **Data Type:** Structured tabular data
- **Format:** CSV

---

### Dataset Features

The dataset contains information about Airbnb listings, including:

- Listing details (name, room type, price, minimum nights)
- Host information
- Neighbourhood and neighbourhood group
- Geographic coordinates (latitude & longitude)
- Availability throughout the year
- Customer reviews and review frequency
- Number of listings managed by each host

---

## Project Workflow

The project follows a structured data analysis pipeline consisting of three major stages:

### 1. Data Understanding & Assessment
- Explored the dataset structure and features.
- Assessed data quality, missing values, duplicates, and data types.
- Identified potential issues and created a data cleaning roadmap.

### 2. Data Cleaning
- Handled missing values and inconsistent data.
- Corrected data types and standardized categorical values.
- Removed invalid records while preserving meaningful outliers.
- Prepared a clean dataset for analysis.

### 3. Exploratory Data Analysis (EDA)
- Performed univariate, bivariate, and multivariate analyses.
- Identified trends in pricing, room types, neighbourhoods, availability, and host activity.
- Generated business insights through statistical analysis and data visualization.

---

## Tools & Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Development Environment:** Jupyter Notebook
- **Version Control:** Git & GitHub
- **Dataset Format:** CSV

---

## Key Findings

- **Manhattan** consistently recorded the highest average Airbnb listing prices, particularly for entire homes and apartments.
- **Entire homes/apartments** were the most expensive room type across all neighbourhood groups, while shared rooms were the most affordable.
- The majority of Airbnb listings were concentrated in **Manhattan** and **Brooklyn**, indicating these are the city's primary short-term rental markets.
- Correlation analysis revealed **weak relationships among most numerical variables**, suggesting that listing prices are influenced more by location and room type than by review or availability metrics.
- A small number of hosts managed a disproportionately large number of listings, highlighting the presence of professional hosts alongside individual property owners.
- Listing availability and minimum stay requirements varied across neighbourhoods and room types, reflecting different hosting strategies and market demand.

---

## Repository Structure

```
airbnb-nyc-data-analysis/
│
├── 01_Data_Understanding_Assessment.ipynb
├── 02_Data_Cleaning.ipynb
├── 03_Exploratory_Data_Analysis.ipynb
├── airbnb_cleaned.csv
├── README.md
└── LICENSE
```

---

## Skills Demonstrated

This project demonstrates the following data analytics skills:

- Data Understanding & Quality Assessment
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Business Insight Generation
- Python Programming
- Data Storytelling
- Git & GitHub Version Control

---

## Dataset Source

The dataset used in this project is publicly available on Kaggle:

**Airbnb NYC Open Data**  
https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data
