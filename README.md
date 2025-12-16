#  Sales Prediction with OLS Regression

## Project Overview
This project analyzes historical sales and advertising data to identify key factors influencing sales performance.  
By applying exploratory data analysis (EDA), correlation analysis, and Ordinary Least Squares (OLS) regression, the project aims to build an interpretable sales prediction model and derive actionable business insights.

The focus of this project is not only predictive performance but also statistical interpretability to support data-driven decision-making.

---

## Objectives
- Understand the relationship between advertising channels and sales
- Identify key drivers that significantly impact sales performance
- Build an interpretable baseline regression model using OLS
- Provide actionable recommendations for marketing budget allocation

---

## Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Statsmodels (OLS Regression)  
- Jupyter Notebook

## Installation
Install required dependencies using:

```bash
pip install -r requirements.txt
```

---

## Project Structure
```text
Sales_Prediction/
├── Sales_Prediction.ipynb   # EDA, visualization, and OLS modeling
├── README.md                # Project documentation
└── requirements.txt         # Project dependencies
```

## Methodology
- Performed data exploration and cleaning, including descriptive statistics and outlier detection using the IQR method
- Conducted exploratory data analysis (EDA) to examine sales and advertising spending distributions
- Analyzed correlations using a heatmap to identify key sales drivers
- Built and refined an OLS regression model based on statistical significance

## Key Results
- R-squared ≈ 0.94, indicating strong explanatory power
- Digital marketing is the strongest sales driver
- TV and radio advertising have moderate positive effects
- Newspaper advertising is not statistically significant

## Business Insights
- Prioritize digital marketing to maximize sales growth
- Use TV and radio as supporting channels
- Reconsider newspaper advertising to optimize marketing ROI

## Notes
- The OLS model assumptions are stated; further diagnostics can be performed if needed
- This model serves as a baseline for future extensions

## Conclusion
This project demonstrates how EDA, correlation analysis, and OLS regression can be used to identify key sales drivers and support data-driven marketing decisions.
