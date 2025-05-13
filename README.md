# week-8-python-project-assignment
# 🦠 COVID-19 Global Data Tracker

A step-by-step data analysis project that explores the global impact of COVID-19 through case counts, deaths, and vaccination progress using Python and data visualization tools.

---

## 📌 Project Overview

This project aims to analyze and visualize the spread of COVID-19 and vaccine rollout across selected countries. It uses real-world data from [Our World in Data](https://ourworldindata.org/coronavirus) and guides you through the process of collecting, cleaning, analyzing, and presenting insights with Python libraries.

---

## 📁 Project Segments

### 1️⃣ Data Collection
- Source: Our World in Data `owid-covid-data.csv`
- Download and save in your working directory.

### 2️⃣ Data Loading & Exploration
- Load the CSV using `pandas`
- Explore data structure, columns, and missing values

### 3️⃣ Data Cleaning
- Filter countries of interest (e.g., Kenya, India, USA)
- Handle missing values and convert date formats

### 4️⃣ Exploratory Data Analysis (EDA)
- Plot total and new cases/deaths over time
- Calculate and visualize death rates

### 5️⃣ Visualizing Vaccination Progress
- Line chart: Cumulative vaccinations
- Bar chart: % population vaccinated
- (Optional) Pie chart per country

### 6️⃣ (Optional) Choropleth Map
- Visualize global vaccination or case data using Plotly

### 7️⃣ Insights & Reporting
- Summarize trends and anomalies using Markdown
- Export notebook to PDF or PowerPoint for presentation

---

## 🧰 Tools & Libraries

- **Python**
- **pandas**
- **matplotlib**
- **seaborn**
- **plotly** (optional for maps)

---

## 🚀 Getting Started

1. Clone this repository or download the code files.
2. Download `owid-covid-data.csv` from [here](https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv).
3. Place the CSV file in the same directory as the notebook.
4. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook covid_global_tracker.ipynb
