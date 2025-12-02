# 🍼 London Birth Trends Analysis

This project analyses **birth patterns across London boroughs** using multiple demographic and socio-economic datasets.  
It combines data on births, ethnicity, deprivation (IMD), housing affordability, gender distribution, and long-term historical live-birth figures.  
The work includes data cleaning, merging datasets, visualising borough-level patterns, and forecasting future birth trends.

The goal of this project is to understand how birth rates vary across London, how they relate to ethnicity, deprivation, and housing conditions, and how these trends have changed over time.

---

## 📁 Datasets Used

This project uses six London-focused datasets, each contributing a different demographic or socio-economic dimension to the analysis.

- **births.csv** — Borough-level birth counts and fertility data  
- **ethnicity.csv** — Ethnic composition of each London borough  
- **gender.csv** — Male and female birth data for sex-based comparisons  
- **housing.csv** — Housing affordability ratios (price-to-income)  
- **md.csv** — IMD 2019 deprivation scores by borough  
- **livebirthsfinal.csv** — Historical live-birth records used for long-term trend modelling  


## 🐍 Python Script Included

- **`analysis.py`**  
  Contains all data cleaning, merging, numeric conversion, visualisations, and forecasting code.

## 🌍 Geographic Scope

All datasets were filtered and standardised to include only the **32 official London boroughs**, ensuring consistent merging and accurate comparisons.

---

## 🧰 Libraries Used

This project uses a set of Python libraries to load data, clean it, merge datasets, run numerical operations, and generate visualisations:

- **pandas** — for data loading, cleaning, merging, and transformation  
- **numpy** — for numerical operations and array-based calculations  
- **matplotlib** — for creating bar charts, pie charts, and trend visualisations  
- **sklearn** — used to build a polynomial regression model for forecasting birth trends  
- **adjustText** — used to prevent label overlap in the bubble chart visualisation  

These libraries support every step of the analysis, from initial preprocessing to final statistical insights and forecasting.

---

## 🎯 Project Objectives

The main goal of this project is to analyse birth patterns across London and understand how they relate to key social and economic factors.  
Using cleaned and merged datasets, the project investigates trends, disparities, and relationships between births, ethnicity, deprivation, and housing affordability.

### **Key Objectives**
- Analyse how birth rates vary across London boroughs
- Compare high-birth and low-birth areas to identify regional patterns
- Understand how ethnicity distributions relate to birth outcomes
- Examine gender differences in birth counts across all boroughs
- Explore how deprivation (IMD scores) correlates with birth levels
- Assess whether housing affordability influences birth rates
- Build a long-term historical trend of London births (1993–2023)
- Produce a short-term forecast (2024–2028) using a polynomial model
- Create clear and meaningful visualisations to support insights

These objectives reflect the core purpose of the project:  
**to understand London’s changing birth landscape using data-driven analysis.**

---

# 🛠️ Python Skills Practiced

Throughout this project, I applied a range of data-handling and analysis skills to explore birth trends and social patterns across London.  
These skills were used directly while cleaning data, merging datasets, and generating visual insights.

### 🔹 Data Cleaning & Preparation
- Standardising column names and fixing inconsistent labels  
- Handling missing values and converting data to numeric types  
- Aligning borough names across multiple independent datasets  

### 🔹 Data Integration
- Merging several datasets (births, ethnicity, deprivation, housing, gender) into one analysis-ready dataframe  
- Ensuring all files shared a consistent structure for accurate comparisons  

### 🔹 Exploratory Data Analysis (EDA)
- Sorting and ranking boroughs by birth rate  
- Summarising population, ethnicity distributions, and IMD scores  
- Calculating weighted metrics based on birth levels  

### 🔹 Visualisation Skills
- Creating bar charts, pie charts, scatter plots, and trend lines  
- Styling visuals for clarity (gridlines, labels, colours, smart annotations)  
- Producing a bubble chart combining affordability, birth rate, and deprivation  

### 🔹 Statistical & Modelling Techniques
- Building a polynomial regression model to forecast future birth trends  
- Using numerical methods to generate weighted ethnicity distributions  
- Identifying relationships between social factors and birth outcomes  

### 🔹 Python & Library Skills
- Working with **pandas** for data cleaning and merging  
- Using **numpy** for numerical operations  
- Visualising insights using **matplotlib**  
- Applying **scikit-learn** for trend forecasting  
- Using **adjustText** to improve readability of plotted labels  

These skills represent the full workflow followed in this project — from raw data to actionable insights.

---

# 🔍 Analysis Highlights

This section summarises the main analyses performed in the project.  
Each highlight corresponds directly to a real chart, calculation, or transformation created in the Python file.
---

## 📊 1. Top & Bottom Boroughs by Birth Rate (2024)
Identified the **five highest** and **five lowest** London boroughs based on 2024 birth-rate values.  
A comparative bar chart highlights regional differences in fertility levels across the city.

<img width="1233" height="736" alt="Screenshot 2025-12-02 at 22 06 31" src="https://github.com/user-attachments/assets/635b79df-db3f-4fdb-8cb6-6cd62af2dd62" />


## 👥 2. Ethnicity-Weighted Birth Distribution (2024)
Calculated the estimated ethnic breakdown of London births by weighting each borough’s ethnic percentages by its birth rate.  
This provides a more accurate representation than population percentages alone.

<img width="801" height="856" alt="Screenshot 2025-12-02 at 22 07 58" src="https://github.com/user-attachments/assets/9aa075c4-6c9a-4885-b220-1202c089a212" />


## 👶 3. Gender-Based Birth Totals
Summed male and female births across all boroughs to reveal overall gender distribution for 2022–2023.  
Presented as a clear two-segment pie chart.

<img width="740" height="627" alt="Screenshot 2025-12-02 at 22 09 48" src="https://github.com/user-attachments/assets/485308ef-77b6-4dd0-8a0b-2b7fa29b5105" />


## 📉 4. Historical Birth Trends & Forecast (1993–2028)
Using real data from 1993–2023, a polynomial regression model was fitted to forecast births up to 2028.  
This shows whether London’s long-term birth trend is rising, stabilising, or declining.

<img width="1483" height="732" alt="Screenshot 2025-12-02 at 22 11 00" src="https://github.com/user-attachments/assets/895512e5-1199-4779-b84e-5bfb3dc9efec" />


## 🏡 5. Housing Affordability vs Birth Rate (Bubble Chart)
Combined housing affordability, birth rate, and deprivation levels into a single visual:

- **X-axis:** Housing affordability ratio  
- **Y-axis:** Birth rate (2024)  
- **Bubble size:** Birth rate  
- **Bubble colour:** IMD deprivation score  

This comparison reveals how socio-economic conditions relate to fertility patterns across boroughs.

<img width="1260" height="857" alt="Screenshot 2025-12-02 at 22 12 03" src="https://github.com/user-attachments/assets/a570e39e-3445-489f-acb8-00745c19fe3e" />


Each analysis is directly based on the merged dataset and reflects realistic demographic insights about London.

---

## 🎓 Learning Outcomes

Working through this project strengthened my ability to work with real-world datasets and extract meaningful insights about London’s birth patterns.  
I gained experience across the full data analysis workflow — from cleaning raw files to building visualisations and forecasting models.

### 🔹 Data Understanding & Preparation
- Learned how to inspect and clean messy datasets  
- Standardised inconsistent column names and borough labels  
- Converted string-based columns into numeric types for accurate analysis  

### 🔹 Multi-Dataset Integration
- Gained confidence merging several independent datasets into a single analytical table  
- Understood how different social indicators (ethnicity, housing, deprivation) relate through shared keys  

### 🔹 Analytical Insight Development
- Identified boroughs with the highest and lowest birth rates  
- Interpreted demographic and socioeconomic patterns behind birth trends  
- Calculated ethnicity-weighted birth contributions for deeper insight  

### 🔹 Visualisation & Communication
- Created clear charts to communicate complex relationships  
- Used bar, pie, scatter, bubble, and trend-line plots effectively  
- Improved data storytelling by adding annotations, colour scales, and structured layouts  

### 🔹 Forecasting & Modelling
- Built a polynomial regression model to project future birth levels  
- Understood how historical data can be used to estimate forward trends  

### 🔹 Practical Python Skills
- Strengthened proficiency with **pandas**, **numpy**, **matplotlib**, **scikit-learn**, and **adjustText**  
- Improved confidence writing reusable functions (e.g., column cleaners)  
- Became more comfortable debugging data issues and validating outputs  

These outcomes reflect the complete learning progression gained from analysing London’s births data using Python.

---

## 📌 Conclusion

The purpose of this project was to analyse **birth patterns across London** using six borough-level datasets.  
By combining births, ethnicity, deprivation (IMD), housing affordability, gender data, and long-term historical records, I created a single, clean dataset that reveals how social and economic factors relate to birth rates.

Using Pandas, NumPy, Matplotlib, Scikit-Learn, and adjustText, I explored:

- which boroughs have the highest and lowest birth rates  
- how ethnicity contributes to London’s birth distribution  
- the balance of male vs female births  
- long-term birth trends and forecasts for 2024–2028  
- how deprivation and housing affordability correlate with fertility  

This project demonstrates my ability to handle real datasets, clean and merge them, create meaningful visualisations, and interpret demographic trends.  
Overall, the analysis provides a clear, data-driven view of how **London’s births vary across boroughs and over time**.

---

## 🖥️ How to Use This Project

This repository contains the full code and datasets used to analyse birth trends across London.

### ▶️ How to Use
1. Open the main Python script to see the full workflow (cleaning → merging → analysis → charts).
2. Make sure all six CSV files are in the same folder as the script.
3. Run the code in Jupyter, Colab, or any Python environment.
4. View the generated charts and outputs to explore the insights.

### 📄 What’s Included
- Cleaned and merged datasets  
- Python code for analysis and visualisations  
- Forecasting model for birth trends  
- Charts comparing ethnicity, gender, housing, and deprivation  
