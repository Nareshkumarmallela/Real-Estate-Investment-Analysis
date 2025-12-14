🏙️ San Francisco Real Estate Valuation & Investment Analysis
📌 Project Overview

This project develops a data-driven real estate valuation framework to identify undervalued residential properties in San Francisco following the 2008 financial crisis. Using predictive modeling and regression analysis, the study supports strategic investment decisions under a $7 million budget constraint, recommending optimal combinations of three properties that maximize potential returns.

The project is framed around a real-world case study — The Milton Campos Investment Challenge — where an investor with limited real estate expertise relies on analytics for decision-making.

🎯 Objectives

Estimate fair market value of residential properties using predictive models

Identify undervalued properties based on price deviation

Compare multiple regression techniques and select the most reliable model

Recommend top 3-property investment combinations within a fixed budget

Provide a transparent and reproducible analytical framework

🗂️ Dataset

Source: San Francisco Properties (XLS924-XLS-ENG.xlsx)

Records: 1,396 property listings

Time Period: February 2008 – July 2009

Price Range: $100,000 – $9,500,000

Key Features

Numerical: Price, Bedrooms, Square Feet, Lot Size

Categorical: Neighborhood (Low/Medium/High), Zip Code, Loft

Temporal: Listing Date

Identifier: Property ID

🛠️ Tools & Technologies

R – Data cleaning, transformation, regression modeling

Power BI – Visualization, ranking investment combinations

Excel – Initial data storage and review

🔍 Methodology
1. Data Preparation

Converted categorical variables to factors

Handled outliers using IQR-based capping

Applied log transformation to correct price skewness

Verified dataset completeness (no missing values)

2. Model Development

Data split: 70% Training / 30% Validation

Models evaluated:

Multiple Linear Regression (MLR)

Stepwise Regression

Regression Tree

3. Model Evaluation

Performance measured using RMSE

Stability and generalization assessed across training and validation datasets

📈 Model Performance Summary

Multiple Linear Regression emerged as the best-performing model due to:

Lowest and most stable RMSE

Strong generalization (no overfitting)

High interpretability and simplicity

💰 Investment Strategy
Price Deviation Formula
Price Deviation = Predicted Price – Actual Price


Positive deviation → Undervalued property

Properties ranked by deviation to identify best opportunities

Investment Constraints

Total Budget: $7 million

Properties: Exactly 3 per investment portfolio

Output

Top 10 three-property combinations ranked by:

Combo Price (sum of actual prices)

Combo Deviation (sum of predicted gains)

🏆 Key Findings

Significant undervaluation exists in post-crisis San Francisco listings

Regression-based valuation is effective in volatile markets

Optimal 3-property combinations maximize return while respecting budget limits

Data-driven approach improves transparency and reduces investment risk

⚠️ Limitations

Relies on historical data; future market shifts not captured

Does not include qualitative factors (property condition, curb appeal)

Requires periodic retraining for continued accuracy

🚀 Future Enhancements

Incorporate time-series analysis for price trends

Add macroeconomic indicators (interest rates, employment)

Explore ensemble models or neural networks

Integrate geospatial analysis for location-based effects
