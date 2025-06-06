# 📊 COVID-19 Data Analysis Project

This project presents a comprehensive analysis of COVID-19 data, with a focus on trends in total cases, deaths, and vaccinations for selected countries. It includes data cleaning, exploration, visualization, and insights — all performed in Google Colab using Python libraries such as `pandas`, `matplotlib`, `seaborn`, and `plotly`.

---

## 📁 Dataset

The dataset is sourced from **Our World in Data** and includes:
- Daily COVID-19 metrics per country (cases, deaths, tests, vaccinations)
- Socioeconomic indicators (life expectancy, HDI, smoking rates)
- Date range: From the beginning of 2020 onwards

---

## 🛠️ Tools & Libraries

- **Python 3**
- `pandas` – data manipulation
- `matplotlib` & `seaborn` – plotting
- `plotly.express` – interactive maps
- `Google Colab` – development environment

---

## 📌 Project Steps

### 1. Data Loading & Exploration
- Load the dataset using `pandas`
- Explore structure, columns, and missing values

### 2. Data Cleaning
- Focused on three countries: **Kenya**, **India**, **USA**
- Handled missing values and converted `date` to datetime format

### 3. Exploratory Data Analysis (EDA)
- Visualized total cases and deaths over time
- Compared new daily cases
- Calculated and analyzed death rates

### 4. Vaccination Analysis
- Compared cumulative vaccinations across countries
- Visualized % vaccinated populations over time

### 5. Choropleth Map (Optional)
- Visualized total cases globally using Plotly
- Mapped `iso_code` to case density by country

### 6. Insights & Reporting
- Summarized key patterns and disparities
- Identified trends in vaccine rollout and case surges

---

## 📈 Sample Visuals

- Line charts for case and death trends
- Bar charts for comparison
- Choropleth map of global cases

---

## 📄 Final Output

- Well-documented Jupyter Notebook
- Includes code, charts, and explanations
- Optional export to PDF or PowerPoint

---

## 🔍 Key Insights

- The U.S. and India had the highest case counts and vaccination rates.
- Kenya’s reporting showed fewer cases but higher relative death rates.
- The pandemic's impact varied widely by geography, infrastructure, and resource access.

---

## 📂 How to Run

1. Open the project in Google Colab/jupyter notebook
2. Upload the CSV dataset
3. Run cells step-by-step to perform the analysis
4. Modify the `countries_of_interest` list to compare different nations

---

## 🧠 Author

Developed by Jesse Ager as part of a data analysis assignment on pandemic trends and response evaluation.

---


