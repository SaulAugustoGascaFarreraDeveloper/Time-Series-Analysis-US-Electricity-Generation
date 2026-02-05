# Time-Series-Analysis-US-Electricity-Generation
Exploratory Data Analysis (EDA) and time series analysis of U.S. electric power generation by source (2001–2025) using data from the U.S. Energy Information Administration (EIA).

# U.S. Electric Power Generation – Time Series Analysis (2001–2025)

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** and **time series analysis** on historical electric power generation data in the United States, measured in megawatt-hours (MWh). The dataset covers multiple electricity generation sources and spans the period from **2001 to 2025**.

The main objective is to identify **long-term trends, stability patterns, and structural changes** across different energy sources, with a focus on understanding the transition toward cleaner and more sustainable energy.

---

## 🎯 Business Objective
The primary business question addressed in this analysis is:

**Have any electricity generation sources remained stable, increased, or decreased their output levels during the 2001–2025 period?**

Answering this question helps:
- Identify long-term energy trends
- Support strategic planning in the energy sector
- Understand the shift toward renewable and low-emission energy sources

---

## 📊 Dataset Description
- **Source:** U.S. Energy Information Administration (EIA)
- **Metric:** Monthly electricity generation (MWh)
- **Time Range:** 2001–2025
- **Generation Sources Include:**
  - Coal
  - Natural Gas
  - Oil
  - Hydroelectric
  - Nuclear
  - Solar (thermal & photovoltaic)
  - Wind
  - Other renewable and thermal sources

---

## 🔗 Data Source
The dataset is publicly available on the **U.S. Energy Information Administration (EIA)** website.

### Steps to download the data:
1. Visit: https://www.eia.gov/electricity/data.php  
2. Navigate to **"Generation and thermal output"**  
3. Download the Excel file: **"Monthly (back to 2001)"**

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas & NumPy** – data cleaning and manipulation
- **Matplotlib & Seaborn** – data visualization
- **Statsmodels** – time series decomposition and analysis

---

## 🔍 Analysis Performed
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Trend and seasonality inspection
- Correlation analysis between generation sources
- Comparative visualization across energy types
- Time series decomposition (additive / STL)

---

## Graphic Examples

<img width="2079" height="671" alt="Screenshot 2026-02-05 171453" src="https://github.com/user-attachments/assets/ca7570cf-ec98-4b5d-9964-5aab707c585c" />

<img width="1266" height="1150" alt="Screenshot 2026-02-05 171509" src="https://github.com/user-attachments/assets/0a011ff4-a091-44cf-8c69-2cc145fe2237" />

<img width="1372" height="543" alt="Screenshot 2026-02-05 171523" src="https://github.com/user-attachments/assets/11213427-290d-4692-bf90-aa156acfe345" />

<img width="1269" height="447" alt="Screenshot 2026-02-05 171539" src="https://github.com/user-attachments/assets/56655c8e-3c9c-49f6-a74b-2a6766bea5bf" />



## 📈 Key Findings
- **Solar and wind generation** show a strong and sustained increase over time.
- **Coal and oil-based generation** exhibit a significant long-term decline.
- **Natural gas** has increased alongside renewable energy adoption.
- **Hydroelectric and nuclear** generation have remained relatively stable throughout the period.
- Correlation analysis suggests that the growth of renewables is associated with reduced reliance on coal.

---

## 🧠 Conclusions
The analysis reveals a **clear structural transition** in the U.S. electricity generation mix from fossil fuel–based sources toward **cleaner and more sustainable energy sources**.

- Renewable energy sources such as **solar and wind** have grown rapidly.
- **Coal and oil** usage has declined sharply.
- **Hydroelectric and nuclear** energy have served as stable baseline sources over the last two decades.

These findings highlight the ongoing energy transition and provide valuable insights for policy-making, energy planning, and sustainability strategies.

---

## 📌 Future Work
- Forecast future generation trends using ARIMA / SARIMA / Prophet
- Analyze seasonal and cyclical patterns in more depth
- Compare U.S. trends with other countries
- Build interactive dashboards for stakeholders

---

## 👤 Author
**Saul Augusto Gasca Farrera**  
Data Scientist | Software Engineer  
