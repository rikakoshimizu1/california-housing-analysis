# California Housing Data Analysis

## Overview
This prokect analyzes the California Housing dataset using Python. The goal is to apply knowledge of Pandas and NumPy to perform data analysis and transformations. This assignment helps familizarize with essential data exploration techniques commonly used in deep learning and data science.

## Objective
The objective of the assigment was to apply knowledge of **Pandas** and **NumPy** to perform data analysis and transformations on the California Housing dataset. The goal was to gain familiarity with essential data exploration techniques used in data science workflows.  

## Dataset
The dataset contains housing data for various districts in California. Each row represents a district and includes features such as **median house value**, **median income**, **population**, and **housing median age**. 

## Features
 - Data loading and cleaning using Pandas
 - Exploratory Data Analysis (EDA) using descriptive statistics and visualizations
 - Use of libraries: **Pandas**, **NumPy**, and **Matplotlib**
 - Visulizations to understand relationships between variables and housing prices

## Analysis and Insights
From the initial analysis and transformations:
 - Normalizing the **median income** and **total rooms** allowed for better identification of outliers. A normalized value of `0` indicates the mean, values `<0` are below average, and values `>0` are above average.
 - Visualizations in Task 5 showed that **lower normalized median income** correlates with **cheaper homes**, while **mediacn or higher income** correlates with **more expensive homes**.
 - The **linear regression model** showed a high **mean squared error (MSE)**, likely due to outliers. However, the **R-squared score**, which is less sensitive to outliers, was between **0.50 and 0.99**, indicating a moderately good fit.
These transformations and visualizations were essential for uncovering patterns in the data and evaluating the model's performance. 

## About
This Jupyter Notebook was completed as part of the **UCSC Silicon Valley Extension Deep Learning and Artificial Intelligence** program.
