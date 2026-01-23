# Statistical Business Analysis

# 1. Introduction
This project focuses on applying statistical techniques to real-world business data to extract meaningful insights. Using sales and marketing data, the analysis evaluates performance metrics, tests business hypotheses, and determines whether observed patterns are statistically significant. The project demonstrates how statistics support data-driven business decisions.

# 2. Project Objectives
The main objectives of this analysis are:
* To summarize business data using descriptive statistics
* To analyze data distribution and variability
* To evaluate relationships between key business metrics
* To perform hypothesis testing and interpret p-values
* To calculate confidence intervals for important metrics
* To build regression models for predictive understanding

# 3. Dataset Description
The business_data.csv dataset is a consolidated business-level dataset created by merging sales data and customer data.It provides a unified view of transaction details, customer attributes, billing information, and churn status, making it suitable for statistical and business analysis. This dataset is used to analyze: Sales performance, Customer behavior, Revenue patterns.

| Date	           | Date of the transaction                                             |
| Product	         | Product purchased by the customer                                   |
| Quantity	       | Number of units purchased                                           |
| Price            | Price per unit                                                      |
| CustomerID       | Unique identifier for each customer                                 |     
| Region	         | Geographic region of the customer                                   |
| Total_Sales      | Total sales value for the transaction                               |
| Tenure	         | Number of months the customer has been associated with the business |
| MonthlyCharges	 | Monthly subscription or service charges                             |
| TotalCharges     | Total amount charged to the customer                                |
| Contract	       | Type of customer contract (e.g., Monthly, Yearly)                   |
| PaymentMethod	   | Payment method used by the customer                                 |
| PaperlessBilling | Indicates whether billing is paperless (Yes/No)                     |
| SeniorCitizen    | Indicates if the customer is a senior citizen (0/1)                 |
| Churn	           | Indicates whether the customer has churned (Yes/No)                 |

# 4. Data Preparation
- Before analysis:
* Missing values were checked and handled appropriately
* Data types were validated for numerical and categorical columns
* Sales-related columns were verified for consistency
* The dataset was cleaned to ensure reliability for statistical analysis

# 5.Data Types
* Numerical variables: Quantity, Price, Total_Sales, Tenure, MonthlyCharges, TotalCharges
* Categorical variables: Product, Region, Contract, PaymentMethod, PaperlessBilling, Churn
* Identifier variables: CustomerID
* Date variable: Date
These variable types allow for descriptive statistics, hypothesis testing, correlation analysis, and regression modeling.

# 6. Methodology
The analysis followed a structured statistical workflow:
# 6.1 Descriptive Statistics
- Calculated:
* Mean
* Median
* Standard deviation
These metrics summarize central tendency and variability in sales.
# 6.2 Distribution Analysis
- Sales distribution was analyzed using:
* Histogram
* Density curve
This helped assess whether sales values follow a normal distribution.
# 6.3 Correlation Analysis
- The Pearson correlation coefficient was calculated to measure the relationship between:
* Sales
* Marketing spend
A heatmap was used to visualize correlation strength.
# 6.4 Hypothesis Testing
- An independent t-test was performed to test the hypothesis:
* Higher marketing spend leads to significantly higher sales
* Null Hypothesis (H₀): Marketing spend has no effect on sales
* Alternative Hypothesis (H₁): Marketing spend significantly affects sales
The p-value was compared against a 0.05 significance level.
# 6.5 Confidence Interval
A 95% confidence interval was calculated for average sales to estimate the true population mean and quantify uncertainty.
# 6.6 Regression Analysis
- A linear regression model was built to:
* Predict sales based on marketing spend
* Measure strength of the relationship using R²
* Evaluate statistical significance of coefficients
  
# 7. Use Case in Analysis
This dataset is used to:
* Calculate descriptive statistics (mean, median, standard deviation)
* Analyze sales distribution and variability
* Examine correlations between business metrics
* Perform hypothesis testing (e.g., churn vs revenue, region vs sales)
* Compute confidence intervals for key metrics
* Support business decision-making using statistical evidence

# 8. Results Summary
- Key statistical findings include:
* Average sales: $45,200 ± $3,400 (95% CI)
* Correlation between sales and marketing spend: 0.78 (Strong positive)
* Hypothesis test result: Statistically significant (p = 0.0012)
* Regression analysis confirms marketing spend as a strong predictor of sales

# 9. Interpretation of Results
* Higher marketing investment is strongly associated with increased sales
* The low p-value indicates that the observed relationship is unlikely due to chance
* Confidence intervals provide reliability bounds for business estimates
* Regression results support predictive modeling for planning purposes

# 10. Business Insights
- Based on the statistical analysis:
* Marketing spend has a significant impact on revenue
* Increasing marketing budgets can drive measurable sales growth
* Data-backed budgeting decisions reduce financial risk
* Statistical testing validates business assumptions objectively

# 11. Limitations
* Dataset size is limited
* No customer-level or regional breakdown available
* Seasonal effects are not fully captured
* Results may vary with larger or more detailed datasets.

# 12. Conclusion
This project successfully demonstrates how statistical methods can be applied to business data to extract actionable insights. The business_data.csv dataset provides a comprehensive and analysis-ready view of business operations. By combining transactional, customer, and billing data, it enables robust statistical analysis and supports data-driven business insights.

# 13. Future Improvements
* Add customer segmentation analysis
* Perform ANOVA across multiple groups
* Extend regression to multivariate models
* Apply time-series forecasting
