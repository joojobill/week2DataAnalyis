# week2DataAnalyis

# Overview

As a software engineer, I am focused on developing the ability to extract meaningful insights from real-world datasets using data analysis tools. This project allowed me to strengthen my skills in data manipulation, transformation, and visualization using Python. My goal was to move beyond basic coding and begin working with structured data in a way that supports decision-making and analytical thinking.

The dataset I analyzed is the Annual Enterprise Survey 2024 Financial Year (Provisional), which contains information about business activity across industries, including income, expenses, and other financial indicators. The dataset was obtained from Stats NZ (New Zealand’s official statistics provider):
https://www.stats.govt.nz/indicators/annual-enterprise-survey

This dataset includes variables such as industry classification codes, financial values, and types of economic measures, making it suitable for aggregation and comparison using Pandas.

The purpose of writing this software was to practice using Pandas to clean, filter, and analyze real-world data. Specifically, I wanted to answer meaningful business-related questions such as which industries generate the most income, how data is distributed across industries, and how aggregation can reveal trends. This helps build practical skills that can be applied in analytics systems, dashboards, or backend services

[Software Demo Video](http://youtube.link.goes.here)

# Data Analysis Results

Question 1: Which industry has the highest average income?
Answer:
The analysis showed that certain industries (based on ANZSIC06 classification) have significantly higher average income values than others. These industries likely represent sectors with high capital intensity or large-scale operations. This was determined using grouping and averaging functions in Pandas.

Question 2: Which industry appears most frequently in the dataset?
Answer:
The most frequent industry category was identified using value counts. This indicates which sectors have the most recorded entries in the dataset, suggesting higher reporting frequency or broader representation in the economy.

Question 3: Which industry generates the highest total income?
Answer:
By summing income values across industries, the analysis showed that industries with a large number of entries tend to generate the highest total income. This highlights the difference between average performance and total economic contribution.

# Development Environment

The development environment used for this project included Visual Studio Code with the Jupyter Notebook extension, which allowed for interactive coding and step-by-step data analysis. This setup made it easier to test code incrementally and visualize outputs immediately.

The programming language used was Python, with the following libraries:

Pandas for data manipulation and analysis
Matplotlib for data visualization

These tools provided efficient methods for handling structured data, performing aggregations, and generating graphical insights.

# Useful Websites

{Make a list of websites that you found helpful in this project}
https://pandas.pydata.org/docs/
https://matplotlib.org/stable/tutorials/index.html
https://www.w3schools.com/python/pandas/default.asp
https://www.stats.govt.nz/indicators/annual-enterprise-survey

# Future Work

{Make a list of things that you need to fix, improve, and add in the future.}
Improve data cleaning by handling missing or inconsistent values more robustly
Add more visualizations such as pie charts or trend analysis
Build an interactive dashboard instead of static analysis
Expand the analysis to include additional variables such as expenses and profit margins
Optimize performance for larger datasets