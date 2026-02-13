# M5 Price Optimization & Revenue Forecasting

I developed this end-to-end pipeline to solve a critical retail challenge: finding the "Sweet Spot" between price and demand. Using Walmart's M5 competition dataset, I demonstrated how data-driven pricing can significantly boost the bottom line.

## 🚀 Project Highlights
* **Scale**: Successfully processed and analyzed a subset of 50M+ rows of retail data.
* **Impact**: Identified an optimal price point yielding a projected **13.4% revenue increase**.
* **Methodology**: Applied Linear Regression to extract price elasticity coefficients after engineering temporal features.

## 🛠️ Technical Workflow
1. **Data Engineering**: Memory-efficient loading and geographic filtering (CA Stores).
2. **Feature Engineering**: Created 7-day rolling averages and sales lags to capture seasonality.
3. **Exploratory Analysis**: Validated price-demand correlations across multiple product categories.
4. **Prescriptive Modeling**: Built a revenue simulation engine to predict the impact of price changes.

## 📂 Repository Contents
* `M5_Forecasting.ipynb`: Interactive Jupyter Notebook containing the full Python pipeline.
* `M5_Forecasting.html`: Static, easy-to-view version of the analysis.
* `price_optimization_model.pkl`: The trained predictive model for deployment.

---
*This project was developed independently as part of a retail analytics portfolio.*
