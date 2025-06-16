# US-Economic--Structural-Analysis
A data-driven analysis of structural shifts in the U.S. economy from 1973-2023.
# U.S. Economic Analysis: A 50-Year Study of Growth, Wages, and Inequality

**Author:** Wil Watkins  
**LinkedIn:** [linkedin.com/in/wilwatkins](https://linkedin.com/in/wilwatkins)  
**Interactive Dashboard:** [(https://public.tableau.com/app/profile/william.watkins5080/vizzes)]

---

### Executive Summary

This project analyzes over 50 years of U.S. economic data to visualize the structural transformations in the American economy. By synthesizing data from the Federal Reserve, the Economic Policy Institute, and academic sources on union density, this analysis reveals a significant **decoupling** of macroeconomic growth from the prosperity of typical workers and families. Key findings illustrate that while GDP and corporate profitability remain tightly linked, the historical relationships between union strength, median income, and executive compensation have fundamentally shifted, contributing to a rise in economic inequality.

### Key Visualization: The Great Decoupling (1973-2023)

(https://github.com/user-attachments/assets/10555d67-cc68-466b-b22f-071c2ad8663e)

---

### Key Questions

This analysis sought to answer the following questions:
1.  How has the relationship between overall economic growth (GDP) and corporate profitability evolved?
2.  What is the relationship between the decline in union density and the rise in both executive compensation and income inequality?
3.  Have the economic gains experienced by the median American family kept pace with overall economic growth and corporate profits?

---

### Key Findings

The analysis revealed three core themes representing a structural shift in the U.S. economy:

* **1. A Stable Economic Core:** The link between Real GDP growth and Real Corporate Profit growth has been the most stable and predictable feature of the economy, with a correlation of +0.97 over 50 years.
* **2. The Great Decoupling:** While the economy has consistently grown, this growth has become disconnected from the prosperity of the median family and the wages of typical workers. The analysis shows the historical, positive correlation between union density and median income growth collapsed after the 1980s.
* **3. Entrenched Inequality:** The modern economic structure is one where high corporate profit growth is now strongly correlated with rising income inequality (Gini Ratio), a relationship that was weak or non-existent in the 1970s.

---

### Methodology

1.  **Data Sourcing:** Acquired time-series data from the FRED API, manually extracted CEO-to-worker pay ratio data from Economic Policy Institute (EPI) reports, and manually extracted union density data from unionstats.com.
2.  **Data Cleaning & Merging:** Used Python (Pandas) to robustly load, clean, and merge the three disparate data sources into a single, unified annual dataset. This involved handling non-standard headers/footers, missing values, and data type conversions.
3.  **Data Transformation:** Adjusted all monetary values for inflation to constant 2023 dollars using the Consumer Price Index (CPI) to allow for accurate year-over-year comparisons.
4.  **Analysis & Visualization:** Conducted a comprehensive exploratory data analysis (EDA) using Python (Seaborn, Matplotlib) to create a correlation heatmap, color-coded time-series scatter plots, rolling correlation charts, and an indexed growth chart to identify and interpret key trends.

---

### Tools & Technologies
* **Languages:** Python, SQL (for conceptual modeling)
* **Libraries:** Pandas, Seaborn, Matplotlib, fredapi
* **Tools:** Google Colab, GitHub, Tableau
