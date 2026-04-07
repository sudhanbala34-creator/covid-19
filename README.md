COVID-19 Data Analysis & Dashboard System
Project Overview

The global spread of COVID-19 created a massive amount of real-time data across countries. This project focuses on analyzing COVID-19 data and building an interactive dashboard to visualize trends, patterns, and insights.
The system uses Python, Pandas, Plotly, and Dash to perform Exploratory Data Analysis (EDA) and generate visual insights.

Objectives
Analyze real-world COVID-19 data
Identify trends and patterns
Compare countries based on cases
Build an interactive dashboard
Provide meaningful insights
Dataset Information

Dataset Name: Corona Virus Report
Source: Kaggle

Selected Columns
Date – Observation date
Country/Region – Country name
Confirmed – Total confirmed cases
Deaths – Total deaths
Recovered – Total recovered cases
Active – Active cases
Removed Columns
Province/State
Latitude
Longitude
Last Update
Incident Rate
Case Fatality Ratio
Technologies Used
Python
Pandas
Plotly
Dash
Project Workflow
1. Data Collection
Load dataset from Kaggle
Select required columns
2. Data Cleaning
Handle missing values
Convert date format
Remove duplicates
3. Data Analysis
Calculate total confirmed cases
Calculate total deaths
Calculate total recoveries
4. Visualization
Line chart – Cases over time
Bar chart – Top countries
Pie chart – Case distribution
Scatter plot – Relationship analysis
Heatmap – Correlation
5. Dashboard
Interactive dashboard using Dash
Country dropdown selection
Dynamic charts
Key Features
Real-time trend visualization
Country-wise comparison
Interactive dashboard controls
Easy-to-understand graphs
How to Run
In Google Colab
Upload dataset file
Run Python code
View graphs
In Local System
Install required libraries
Run the Python file
Open dashboard in browser
Project Structure

project/
│── app.py
│── covid_sample_dataset.csv
│── requirements.txt
│── README

Insights
COVID-19 cases increased rapidly over time
Some countries were highly affected
Recovery rates improved gradually
Strong relationship between confirmed and deaths
Conclusion

This project helps understand COVID-19 trends using data visualization. The dashboard provides a simple and interactive way to analyze pandemic data and supports better decision-making.

Acknowledgement
Kaggle for dataset
Python open-source libraries
