# San Francisco Real Estate Valuation & Investment Analysis

## Project Description
This project develops a data-driven real estate valuation framework to identify undervalued residential properties in San Francisco following the 2008 financial crisis. Using regression-based predictive modeling, the analysis supports strategic investment decisions under a $7 million budget constraint by recommending optimal combinations of three properties.

The project is based on the Milton Campos Investment Challenge, where analytics-driven valuation replaces subjective decision-making.

---

## Objectives
- Estimate fair market values of residential properties
- Identify undervalued properties using predictive analytics
- Compare multiple regression models and select the best-performing model
- Recommend three-property investment combinations within a fixed budget
- Provide a transparent and reproducible analytical framework

---

## Dataset Overview
- Total Listings: 1,396 residential properties
- Time Period: February 2008 – July 2009
- Price Range: $100,000 – $9,500,000

### Features Used
- Numerical: Price, Bedrooms, Square Feet, Lot Size
- Categorical: Neighborhood, Zip Code, Loft
- Temporal: Listing Date

---

## Tools and Technologies
- R: Data cleaning, transformation, and regression modeling
- Power BI: Visualization and investment ranking
- Excel: Source dataset management

---

## Methodology

### Data Preparation
- Converted categorical variables to factors
- Treated outliers using IQR-based capping
- Applied log transformation to price
- Verified dataset completeness (no missing values)

### Modeling Approach
- Train-validation split: 70% training, 30% validation
- Models evaluated:
  - Multiple Linear Regression
  - Stepwise Regression
  - Regression Tree

### Evaluation Metric
- Root Mean Square Error (RMSE)

---

## Model Performance
Multiple Linear Regression achieved the lowest and most stable RMSE across both training and validation datasets. Its strong generalization ability and interpretability make it the most reliable valuation model for this study.

---

## Investment Strategy

### Price Deviation Formula
Price Deviation = Predicted Price – Actual Price

- Positive deviation indicates an undervalued property
- Properties ranked based on deviation

### Investment Constraints
- Total Budget: $7 million
- Number of Properties: 3

### Output
- Top 10 three-property combinations ranked by:
  - Combined purchase price
  - Combined price deviation

---

## Key Insights
- Post-crisis San Francisco listings show significant undervaluation
- Regression-based valuation performs well in volatile markets
- Portfolio-level optimization improves investment outcomes
- Data-driven decisions reduce bias and risk

---

## Limitations
- Analysis is based on historical data only
- Qualitative property attributes are not included
- Requires retraining with updated data for future use

---

## Future Enhancements
- Time-series modeling for price trends
- Integration of macroeconomic indicators
- Advanced models such as ensemble methods or neural networks
- Geospatial analysis for location-based valuation

---

## Repository Structure

├── San Francisco Housing Investment Analysis.Rmd<br>

├── San-Francisco-Real-Estate-Valuation_Final.pptx<br>

├── SF_Real_Estate_Valuation_Proposal.docx<br>

├── README.md<br>


---

## Author
Naresh Kumar Mallela  
University of New Haven  

---

## License
This project is intended for academic and educational purposes.
Reuse is permitted with proper attribution.
