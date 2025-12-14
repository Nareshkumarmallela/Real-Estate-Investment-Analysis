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


## About Me
I'm a Data Analyst...


# Hi, I'm Naresh! 👋

Highly motivated and results-driven Data Analyst with a passion for transforming data into actionable insights. While transitioning into the professional data analytics field, I bring a robust foundation in technical skills honed through extensive personal projects and self-directed learning. These skills include:

**Data Visualization:** Expert in Power BI, capable of designing clear, impactful dashboards that drive decision-making.

**Data Analysis:** Proficient in R programming, Python, and SQL for advanced data manipulation and in-depth analysis.

**Data Wrangling and Cleaning:** Skilled in organizing and cleaning complex datasets using tools like Excel, R and Python to ensure data integrity.

**Database Management:** Experienced in designing, managing, and querying databases to efficiently store and retrieve data.

**Data Reporting and Presentation:** Highly adept at delivering compelling data narratives through interactive dashboards and concise reports using Power BI.

A fast learner and dedicated professional, I am committed to contributing to data-driven decision-making and eager to apply my skills to tackle challenging real-world business problems.
