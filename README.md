# Uncovered Interest Parity Analysis: USD/NOK

This project tests the Uncovered Interest Parity (UIP) theory using historical data for USD/NOK exchange rates and interest differentials.

## 📌 Summary

- Modeled UIP using macroeconomic time series data from FRED and Norges Bank  
- Performed OLS regression to evaluate the relationship between expected exchange rate changes and interest rate differentials  
- Analyzed deviations from UIP during monetary policy divergence periods  
- Interpreted results in the context of capital flows and risk premium  
- Created data visualizations to support findings

## 🔧 Tools Used

- R  
- tidyverse  
- ggplot2  
- readxl / quantmod  
- RMarkdown

## 📊 Files

- `uip_model.R`: Data wrangling, regression model, and visualization  
- `uip_analysis_report.Rmd`: Full project write-up (knit to PDF or HTML)

## 🗂️ Data Sources

- [FRED](https://fred.stlouisfed.org/)  
- [Norges Bank](https://www.norges-bank.no/en/)  

## 🚀 Findings

Despite UIP's theoretical expectations, our model found significant and persistent deviations, likely due to market risk premiums or investor behavior.

---

# UIPUSNO-
