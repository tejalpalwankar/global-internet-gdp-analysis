# 🌍 Global Trends in Internet Usage, GDP, and Employment

---

## 📌 Project Summary

This project explores the **interconnected trends** among global internet usage, GDP per capita, and employment rates. Using Python scripting, the team conducted a thorough analysis to understand how digital access impacts economic development and job markets across countries and years.

---

## 🎯 Objectives

- Analyze global trends in internet penetration, GDP per capita, and employment rates.
- Explore correlations between internet usage and GDP growth.
- Examine how digital infrastructure influences job creation.
- Use data visualization to extract insights and support policy implications.

---

## 📁 Data Sources

All datasets were sourced from [United Nations Data](https://data.un.org):

- **Internet Usage Dataset** (2004–2019): `% of population using internet`
- **GDP per Capita Dataset** (2004–2019): economic output per individual
- **Employment Dataset**: employment rates by country and gender

---

## 🧪 Hypotheses

1. Higher internet penetration leads to faster GDP growth.
2. Increased internet access reduces unemployment via online work.
3. Higher GDP per capita is linked to lower unemployment.
4. Internet usage amplifies GDP's impact on employment creation.

---

## 🔧 Preprocessing Steps

- Removed irrelevant columns and cleaned missing data.
- Standardized column names across datasets.
- Merged data on `Country` and `Year`.
- Focused analysis on 4 years: **2004, 2009, 2014, 2019**.
- Used Pandas, NumPy, Seaborn, and Matplotlib for analysis.

---

## 📊 Key Questions Answered

- Which countries had the highest/lowest internet usage in key years?
- How did GDP and employment evolve in high vs. low internet-access regions?
- What is the correlation between GDP and internet usage?
- Are there regional outliers or trends across time?

---

## 📈 Visualizations Produced

- **Scatter plots**: Internet usage vs GDP per capita
- **Histograms**: GDP and internet usage distributions
- **Time-series plots**: Trends across top and bottom countries
- **Correlation heatmaps**: GDP, employment, internet usage

---

## 💡 Key Findings

- **Bahrain** had the highest internet usage in 2019 (99.70%).
- **Burundi** and **Eritrea** had among the lowest access rates.
- **Malaysia** topped GDP per capita in some rankings (subject to validation).
- Strong positive correlation between internet usage and GDP per capita.
- Countries with better digital infrastructure showed lower unemployment and stronger job markets.
- A digital divide remains evident across regions, often aligned with economic inequality.

---

## 🧠 Insights & Implications

- 🌐 **Digital connectivity drives productivity** and opens job markets.
- 💼 **Economic stability enhances employment**, and vice versa.
- 🧩 Interconnected feedback loop between infrastructure, GDP, and jobs.
- 📢 **Policy recommendation**: Invest in digital infrastructure to reduce inequality and foster inclusive growth.


---

## ⚙️ How to Run

1. Clone the repo and open the Jupyter Notebook:
   ```bash
   git clone https://github.com/your-username/global-digital-gdp-project.git
   cd global-digital-gdp-project
   jupyter notebook
