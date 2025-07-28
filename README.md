# Restaurant Risk & Performance Analysis

This project analyzes operational and sales data from a fictional restaurant franchise network to identify early warning signs of underperformance and assess the likelihood of ownership changes. It was completed as part of the University of Queensland course **BSAN7204: Data Analytics**.

The analysis combines exploratory data techniques, regression models, and time series decomposition to extract practical insights for franchisors.

---

## Project Objectives

- Identify patterns associated with customer volume and restaurant sales
- Explore whether poor performance leads to ownership change
- Build predictive models to flag high-risk restaurants
- Use time series analysis to assess trends and seasonal patterns

---

## Key Findings

- Sold restaurants tended to have **more customers but lower food quality**.
- **Higher prices** were significantly linked to **fewer customers**.
- **Suburban locations**, **low food ratings**, and **lower prices** predicted a higher likelihood of sale.
- The **log-transformed regression model** explained **89%** of variance in customer count.
- Time series analysis showed **strong growth trends**, indicating some sales may be **strategic** rather than distress-driven.

---

## Techniques Used

- Exploratory Data Analysis (density plots, box plots, correlation)
- Multiple Linear Regression (stepwise, log-transformed, polynomial)
- Logistic Regression & ROC Curve (classification of sale status)
- Time Series Decomposition (trend, seasonality, noise)
- R packages: `ggplot2`, `dplyr`, `caret`, `pROC`, `MASS`, `GGally`

---

## Repository Structure
Restaurant-Risk-Analysis/
├── README.md # Project overview
├── Restaurant_Risk_Report.pdf # Final report
├── franchise_risk.Rmd # R Markdown with code and narrative
├── franchise_risk.html # HTML output of report
├── Restaurants.csv # Sample dataset
├── Customers.csv # Monthly time series data
├── figures/ # Exported visualisations
├── scripts/ # Modular or test R scripts
└── appendix/ # Model outputs, additional results

---

## Final Report

[Click here to view the full PDF report](./Restaurant_EDA_Report.pdf)

---

## Reflections

This project enhanced my ability to:
- Clean and analyze operational datasets
- Interpret regression and classification models
- Combine static insights with temporal patterns for a dynamic risk assessment
- Build a narrative that blends quantitative evidence with strategic business implications

Future extensions could include forecasting, churn modelling, or dashboard development for franchisor decision support.

---

## Author

**Madeline Coert**  
Graduate Certificate in Business Analytics — University of Queensland  

📍 Brisbane, Australia  
📧 madelinecoert@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/madeline-coert-546667309)  
