# Pymaceuticals Module 5: Data Analysis and Visualization

**Date:** 2024-04-04  
**Author:** Sultan Raheem  
**Instructor:** Bharat  
**Teaching Assistants:** Sunil Khambaita, Divya Suthraye  
**Course:** UofT SCS Data Analytics Boot Camp

---

## Project Overview

This project analyzes experimental data from a drug study on mice, focusing on tumor volume changes across various treatment regimens. The goal is to clean and summarize the data, visualize key statistics, identify outliers, and explore relationships between variables using statistical and machine learning techniques.

---

## Requirements & Deliverables

### 1. Prepare the Data (20 points)
- Merge datasets into a single DataFrame  
- Show number of mice in merged and cleaned DataFrames  
- Identify and remove duplicate mice based on Mouse ID and Timepoint  

### 2. Generate Summary Statistics (15 points)
- Calculate mean, median, variance, standard deviation, and SEM of tumor volumes per treatment regimen  
- Create a new DataFrame containing these summary statistics  

### 3. Create Bar Charts and Pie Charts (15 points)
- Bar plots (Pandas and matplotlib) showing total timepoints per drug regimen  
- Pie charts (Pandas and matplotlib) showing female vs male mice distribution  

### 4. Calculate Quartiles, Find Outliers, and Create Box Plot (30 points)
- Generate a DataFrame of the last timepoint for each mouse  
- Identify interquartile range (IQR) and outliers for key treatment groups  
- Create box plot showing final tumor volume distribution for treatment groups  

### 5. Create Line Plot and Scatter Plot (10 points)
- Line plot of tumor volume over time for a mouse treated with Capomulin  
- Scatter plot showing average tumor volume vs. mouse weight for Capomulin group  

### 6. Calculate Correlation and Regression (10 points)
- Calculate correlation coefficient and perform linear regression on mouse weight vs. average tumor volume for Capomulin regimen  

---

## Work Cited

- https://stackoverflow.com/questions/20130227/how-to-connect-scatterplot-points-with-line-using-matplotlib  
- https://www.w3schools.com/python/ref_func_round.asp  
- https://matplotlib.org/stable/gallery/pie_and_polar_charts/bar_of_pie.html  
- https://chat.openai.com/share/dad7a4a1-8a79-4404-a3de-ad1933481d7d  
- https://pandas.pydata.org/docs/user_guide/merging.html  
- https://www.geeksforgeeks.org/bar-plot-in-matplotlib/  
- https://note.nkmk.me/en/python-statistics-mean-median-mode-var-stdev/  
