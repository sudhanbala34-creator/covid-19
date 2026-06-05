# COVID-19 Data Analysis and Interactive Dashboard

## Project Overview

The manual analysis of large-scale COVID-19 data is challenging and time-consuming. This project automates data cleaning, processing, and Exploratory Data Analysis (EDA) to understand global pandemic trends. An interactive dashboard is developed to visualize confirmed cases, deaths, recoveries, and active cases across different countries and time periods.

---

## Dataset Information

**Source:** Kaggle

**Dataset Name:** Corona Virus Report (COVID-19 Dataset)

**Dataset Link:** Kaggle COVID-19 Dataset

### Features Used for Analysis

To improve performance and simplify analysis, only the following essential features were selected:

* **Date** – Observation date
* **Country/Region** – Country name
* **Confirmed** – Total confirmed cases
* **Deaths** – Total deaths
* **Recovered** – Total recovered cases
* **Active** – Active cases

**Note:** Columns such as Province/State, Latitude, Longitude, and other unnecessary attributes were removed to optimize dashboard performance.

---

## Objectives

### 1. Data Collection and Cleaning

* Load the dataset
* Handle missing values
* Format date fields
* Remove duplicate records

### 2. Descriptive Statistics

* Calculate total confirmed cases
* Calculate total deaths
* Calculate total recoveries
* Compute mortality and recovery rates

### 3. Trend Analysis

* Analyze case growth over time
* Identify pandemic peaks and waves
* Track recovery and death trends

### 4. Country-Wise Analysis

* Compare affected countries
* Identify top countries based on confirmed cases
* Analyze country-level recovery and death statistics

### 5. Relationship Analysis

* Study relationships between variables
* Analyze Confirmed vs Deaths
* Analyze Confirmed vs Recovered cases

### 6. Interactive Dashboard Development

* Create a dashboard using Plotly Dash
* Add country filters
* Add date range selection
* Enable interactive visual exploration

---

## Visualizations Used

### Line Chart

* Displays COVID-19 trends over time
* Shows pandemic waves and growth patterns

### Bar Chart

* Compares top affected countries
* Highlights countries with the highest confirmed cases

### Pie Chart

* Shows distribution of:

  * Active Cases
  * Recovered Cases
  * Death Cases

### Scatter Plot

* Analyzes relationships between variables
* Example: Confirmed Cases vs Deaths

### Correlation Heatmap

* Displays correlation among numerical features
* Identifies strong and weak relationships

---

## Technologies Used

* Python
* Pandas
* NumPy
* Plotly
* Dash
* Google Colab

---

## How to Run the Project in Google Colab

### Step 1: Clone the Repository

```bash
!git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
%cd YOUR_REPOSITORY_NAME
```

### Step 2: Install Required Libraries

```bash
!pip install dash plotly pandas numpy
```

### Step 3: Run the Dashboard

Use JupyterDash or expose the local server port within Google Colab to view the interactive dashboard.

---

## Output

* Cleaned COVID-19 dataset
* Statistical analysis results
* Interactive dashboard
* Trend and comparison visualizations

---

## Key Insights

* Identifies global COVID-19 trends
* Highlights the most affected countries
* Tracks recovery and mortality patterns
* Supports data-driven pandemic analysis

---

## Future Enhancements

* Real-time COVID-19 data integration
* Advanced forecasting using Machine Learning
* Deployment on cloud platforms
* Enhanced dashboard with additional filters and analytics
* 
Visualization
<img width="1682" height="655" alt="image" src="https://github.com/user-attachments/assets/4b6df3f7-3bbd-413e-a6b3-367324a0747f" />
<img width="1681" height="657" alt="image" src="https://github.com/user-attachments/assets/e7d61d7b-d00b-4448-bf84-be9a210be952" />
<img width="1686" height="665" alt="image" src="https://github.com/user-attachments/assets/c4b9df1b-e98f-43fd-ab54-db6cbc1b3f2b" />
<img width="1672" height="653" alt="image" src="https://github.com/user-attachments/assets/0c122c7f-1d07-4c01-ac2f-e9f78134ed85" />


