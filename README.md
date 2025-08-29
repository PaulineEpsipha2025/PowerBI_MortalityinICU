# Mortality in ICU Dashboard – Power BI

## Project Overview
This project explores patient data from the **MortalityInICU dataset** (PhysioNet) to provide actionable insights into ICU patient outcomes. The dashboard highlights key trends and correlations in patient vitals, lab results, and mortality rates to support clinical decision-making and hospital resource management.

## Features
- Interactive Power BI dashboard with slicers for filtering by:
  - Patient demographics
  - ICU type
  - Clinical variables
- Visualizations include:
  - Mortality rate by age, BMI, and comorbidities
  - Correlation between vital signs (heart rate, respiratory rate, etc.) and mortality
  - ICU resource utilization metrics
- Drill-through functionality to explore individual patient outcomes
- Cleaned and preprocessed dataset to ensure accuracy and reliability of analysis

## Tools & Technologies
- **Power BI** – Data visualization and interactive dashboard creation
- **Python / Excel** – Data cleaning, preprocessing, and exploratory analysis
- **PhysioNet MortalityInICU dataset** – Publicly available ICU patient dataset

## Data Preparation
- Removed duplicate records and handled missing values
- Standardized numeric and categorical variables
- Aggregated patient vitals to calculate mean and trends
- Generated derived metrics such as:
  - Mortality rate
  - BMI categories
  - ICU stay duration

## Key Insights
- Mortality rates were higher in patients with extreme BMI values
- Certain vital signs (e.g., elevated heart rate, low GCS scores) strongly correlated with mortality
- ICU type and length of stay were significant factors in patient outcomes

## How to Use
1. Download the Power BI dashboard `.pbix` file from this repo
2. Open it in **Power BI Desktop** (free version available)
3. Use the slicers and filters to explore patient trends and mortality insights

## License
This project is for educational purposes. Data sourced from **PhysioNet**.
