# California Housing Data Analysis

## Overview
This project analyzes the California Housing dataset using **Python**, focusing on applying data exploration techniques with `pandas` and `NumPy`. The goal is to perform a series of transformations and build a simple **linear regression model** to understand how various features influence **housing prices** in California.

## Objective
The objective of this assignment was to apply knowledge of `pandas` and `NumPy` to perform **data analysis and transformations** on the **California Housing** dataset. This included filtering, normalizing values, visualizing distributions, and building a **regression model** to identify patterns in the data. 

## Dataset
The dataset contains housing data for various districts in California. Each row represents a district and includes features (among others):
 - `median_house_value`
 - `median_income`
 - `total_rooms`
 - `population`
 - `housing_median_age`

## Features
 - **Data loading and cleaning** using `pandas`
 - **Exploratory Data Analysis (EDA)** using **descriptive statistics and visualizations**
 - Use of libraries: `pandas`, `NumPy`, and `matplotlib`
 - **Visualizations** to understand relationships between variables and housing prices

## Challenges
 - Handling **missing data** and **outliers** was critical to ensuring accurate results.
 - Choosing the **right features to normalize** required experimentation.
 - Scatter plots were visually noisy, making it difficult to interpret patterns due to overlapping data points. 
 - The **linear regression model** showed a **high mean squared error (MSE)**, likely due to outliers affecting the results, which made interpretation challenging. 

## Analysis and Insights
From the initial analysis and transformations:
 - Normalizing the `median_income` and `total_rooms` helped reveal outliers. A normalized value of `0` indicates the mean, values `<0` are below average, and values `>0` are above average.
 - Visualizations in Task 5 showed that **lower normalized median income** generally correlates with **cheaper homes**, while **meadian or higher income** correlates with **more expensive homes**.
 - The **linear regression model** showed a high **mean squared error (MSE)**, likely due to outliers. However, the **R-squared score**, which is less sensitive to outliers, was between **0.50 and 0.99**, indicating a moderately acceptable fit given the dataset's complexity.

These transformations and visualizations were essential for uncovering patterns in the data and evaluating the model's performance. 

## About
This Jupyter Notebook was completed as part of the **UCSC Silicon Valley Extension Deep Learning and Artificial Intelligence** program.
