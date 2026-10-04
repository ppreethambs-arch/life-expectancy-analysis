# Life Expectancy Analysis

## 📌 Project Overview

This project analyzes life expectancy across 179 countries using demographic, health, education, economic, and healthcare-related indicators.

The analysis was performed using Python and focuses on identifying the major factors associated with differences in life expectancy between countries.

## 🎯 Objectives

- Analyze the distribution of life expectancy across countries
- Compare life expectancy across different regions
- Compare developed and developing economies
- Study the relationship between GDP and life expectancy
- Analyze the impact of schooling and mortality indicators
- Examine the relationship between healthcare and immunization indicators
- Identify the strongest factors associated with life expectancy

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Key Findings

| Factor | Correlation with Life Expectancy |
|---|---:|
| Schooling | +0.738 |
| Polio | +0.682 |
| Diphtheria | +0.667 |
| GDP per Capita | +0.595 |
| BMI | +0.594 |
| Adult Mortality | -0.947 |
| Under-Five Deaths | -0.927 |
| Infant Deaths | -0.925 |
| HIV Incidents | -0.552 |

### Main Insights

- Schooling has a strong positive association with life expectancy.
- Higher immunization levels are associated with higher life expectancy.
- GDP per capita shows a positive relationship with life expectancy.
- Adult mortality has the strongest negative association with life expectancy.
- Infant and under-five mortality are strongly negatively associated with life expectancy.
- HIV incidence also shows a negative relationship with life expectancy.
- Population size has almost no linear correlation with life expectancy in this dataset.

> Note: Correlation indicates association and does not necessarily imply causation.

## 📁 Project Files

- `Life_Expectancy_Analysis.ipynb` — Complete Python analysis and visualizations
- `Life-Expectancy-Data-Averaged.csv` — Dataset used for the analysis

## 📈 Analysis Includes

- Data quality assessment
- Life expectancy distribution
- Regional comparison
- Economic status comparison
- GDP analysis
- Schooling analysis
- Adult mortality analysis
- Infant and under-five mortality analysis
- HIV analysis
- Immunization analysis
- Correlation analysis
- Summary dashboard

## 🔍 Dataset

The dataset contains information about countries and indicators related to health, education, economy, mortality, immunization, and life expectancy.

The dataset contains **179 country observations** and **20 original variables**.

## 🚀 Conclusion

The analysis shows that life expectancy is strongly associated with education, healthcare coverage, economic conditions, and mortality indicators.

The strongest relationships were observed for adult mortality, infant mortality, under-five mortality, schooling, and immunization indicators.

This project demonstrates an end-to-end exploratory data analysis workflow using Python, including data cleaning, statistical analysis, visualization, correlation analysis, and insight generation.
