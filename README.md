# covid-data-analysis-exercise
Exploratory analysis of COVID-19 trends using Python, pandas and matplotlib.

## Overview

This project analyzes COVID-19 data to explore infection trends and compare the evolution of the pandemic across different countries.
Using Python and common data analysis tools, the notebook performs data cleaning, exploratory data analysis, visualization, and simple analytical insights.

The analysis focuses on three countries:

* Peru
* Chile
* United States

The goal is to understand how the pandemic evolved over time and identify patterns such as infection waves and peak periods.

---

## Dataset

The dataset used in this project comes from **Our World in Data**:

https://ourworldindata.org/covid-cases

To run the analysis:

1. Download the dataset from the Our World in Data website.
2. Save the file as:

owid-covid-data.csv

3. Place the file in the same directory as the notebook:

covid_data_analysis.ipynb

The notebook expects the dataset to be named owid-covid-data.csv.

---

## Tools and Libraries

The project was implemented using:

* Python
* pandas
* matplotlib
* Jupyter Notebook

These tools were used for data manipulation, visualization, and exploratory analysis.

---

## Project Structure

The notebook follows a typical data analysis workflow:

1. **Introduction**
   Description of the project and its objectives.

2. **Data Loading**
   Importing the dataset and initial inspection.

3. **Exploratory Data Analysis (EDA)**
   Understanding the dataset structure, missing values, and basic statistics.

4. **Data Cleaning**
   Selecting relevant columns, converting data types, and preparing the data for analysis.

5. **Analysis**

   * Comparison of cumulative COVID-19 cases across countries
   * Visualization of daily new cases
   * Identification of peak infection days

6. **Conclusions and Insights**
   Interpretation of the results and identification of key patterns in the data.

---

## Key Insights

Some of the main observations from the analysis include:

* The United States experienced the largest outbreak in absolute terms among the selected countries.
* Peru and Chile show broadly similar cumulative case trends, although their daily peaks differ in magnitude.
* All three countries experienced multiple waves of infection, visible in the daily new cases data.
* The highest daily infection peaks occurred around early 2022, reflecting a major global surge during that period.

---

## How to Run the Project

1. Download the dataset from Our World in Data.
2. Open the notebook covid_data_analysis.ipynb in Jupyter Notebook.
3. Run the cells sequentially to reproduce the analysis and visualizations.

---

## Author
Sandra

Created as a data analysis exercise using Python and pandas.
