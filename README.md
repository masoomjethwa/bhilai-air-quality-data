
---
# 🌫️ Air Pollutant Data Analysis & Visualization in Bhilai, India  
*A Comprehensive Exploratory Study of Air Quality Trends*

---

## 📌 1. Overview

This repository hosts a comprehensive exploratory data analysis (EDA) and visualization project focused on **air pollutant data from Bhilai, India**. The project aims to provide **deep insights into pollutant concentrations**, their **temporal trends**, and **inter-relationships**, which are crucial for **environmental policy-making** and **public awareness**.

The core of this project is a Python script that:
- Cleans raw data
- Performs extensive analysis
- Generates **40+ publication-ready charts**

---

## 📁 2. Dataset

**Primary file**: `consolidated_pollutant_data_bhilai.csv`

**Key columns:**
- `Date`: Measurement date
- `Sheet`: Source sheet name (station/period)
- `Location`: Data collection location (assumed Bhilai)
- `NO2`: Nitrogen Dioxide (μg/m³)
- `SO2`: Sulfur Dioxide (μg/m³)
- `PM10`: Particulate Matter 10 (μg/m³)
- `PM2.5`: Particulate Matter 2.5 (μg/m³)
- `O3_8hrs`: Ozone 8-hour avg (μg/m³)
- `CO_8hrs_mg_m3`: Carbon Monoxide 8-hour avg (mg/m³)
- `NH3`: Ammonia (μg/m³)
- `Pb`: Lead (μg/m³)

Data is **cleaned** for missing values and correct types before visualization.

---

## 🎯 3. Project Objectives

- Implement robust **data loading and cleaning**
- Generate **40+ high-quality visualizations**
- Analyze:
  - Pollutant **distributions**
  - **Temporal patterns** (daily, weekly, monthly, yearly)
  - **Correlations** among pollutants
  - **Outliers and seasonal trends**

---

## 📂 4. Repository Structure

├── consolidated_pollutant_data_bhilai.csv # Raw data
├── analysis_of_bhillai_data.py # Main Python script
├── cleaned_data/
│ └── cleaned_pollutant_data_bhilai.csv # Cleaned data
└── charts_output/
├── chart_1_hist_NO2.png
├── chart_2_hist_SO2.png
└── ... (40+ chart images)



## ⚙️ 5. Setup & Installation

### ✅ Prerequisites:
- Python 3.8+
- Git
- pip or virtual environment tool

### 📥 Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

## ⚙️ 5. Setup & Installation

### ✅ Prerequisites:
- Python 3.8+
- Git
- pip or virtual environment tool

### 📥 Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


python -m venv venv
# On Windows
.\venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

pip install pandas matplotlib seaborn pathlib statsmodels scikit-learn


📂 Place the data file:
Ensure consolidated_pollutant_data_bhilai.csv is in the project root.

▶️ 6. How to Run
Execute the main Python script:

python analysis_of_bhillai_data.py


What it does:
Loads and cleans the data

Saves cleaned CSV to: cleaned_data/cleaned_pollutant_data_bhilai.csv

Generates 40+ charts into: charts_output/

Prints progress updates to the console

📊 7. Key Visualizations & Insights
Examples below are illustrative. Update with your actual findings.

Pollutant Distributions:
Histograms (e.g., chart_1_hist_NO2.png) show skewed or normal concentration patterns.

Temporal Trends:
Time series plots (e.g., chart_6_timeseries_NO2.png) and monthly averages (chart_11_monthly_avg_pm10.png) reveal trends and seasonal behavior.

Daily Patterns:
Weekly boxplots and strip plots (e.g., chart_14_weekly_avg_so2.png) uncover weekday-weekend variations.

Correlations:
A correlation heatmap (chart_16_correlation_heatmap.png) uncovers strong relationships, e.g., PM10 ↔ PM2.5.

Data Source Comparison:
Stacked bar charts (chart_38_stacked_bar_avg_pollutant_by_sheet.png) compare pollution across locations.

Outlier Detection:
Z-score based plots (chart_37_zscore_outlier_no2.png) highlight anomalies or exceptional pollution days.

📈 8. Advanced Visualization Suggestions
You can extend this project using the following advanced EDA plot types:

Type	Plot Name
Distribution	Violin Plot, ECDF, Boxen Plot
Time Series	Seasonal Decomposition, ACF/PACF, Lag Plot
Multivariate	Pairplot, Heatmap, Radar Plot, MDS, UMAP
Outlier Detection	Isolation Forest, SHAP Summary Plot
Categorical Comparison	Mosaic Plot, Swarm Plot, Catplot
Model Explainability	Partial Dependence Plot, SHAP
Interactive Dashboards	Plotly, Streamlit, Altair, Bokeh

📌 9. Conclusion & Future Work
This project provides a strong exploratory foundation for air quality analysis in Bhilai.

✨ Future Enhancements
✅ Forecasting: ARIMA, Prophet, LSTM for pollution predictions

✅ Geospatial Mapping: Pollution hotspots on Bhilai maps

✅ Compliance Assessment: Against CPCB/WHO standards

✅ Interactive Dashboards: Dash or Streamlit for web-based exploration

✅ Pollution Source Analysis: With meteorological integration

👤 10. Author
Codernumber1
With assistance from: Coding Assistant ID: 85317

📄 11. License
This project is open-sourced under the MIT License.
Feel free to fork, modify, and use for research or educational purposes.

