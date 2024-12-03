# Comprehensive-Risk-Analysis-Report-for-Loan-Defaults

Project Overview

This project provides a data-driven examination of factors influencing loan defaults, aiming to enhance risk assessment strategies for lending institutions. Using a dataset with 148,670 records and diverse attributes such as loan details, borrower demographics, property values, and credit scores, the analysis uncovers key risk indicators and actionable insights.

# Objective

The primary aim of this analysis is to identify key risk factors contributing to loan defaults and provide actionable insights to enhance risk assessment strategies for lending institutions.

# Dataset Features

The dataset used in this analysis contains 148,670 records with 20 columns. Key attributes include:

* Loan Details: Loan type, purpose, amount, and interest rate.
* Borrower Information: Gender, age, income, and credit score.
* Property Details: Property value and occupancy type.
* Default Status: Whether the borrower defaulted (binary outcome).

The dataset includes missing values, which were imputed using statistical techniques to preserve data integrity.

# Highlights

* Comprehensive EDA, including univariate, bivariate, and multivariate analysis.
* Feature engineering to derive meaningful insights from Loan-to-Value (LTV) ratios, Debt-to-Income (DTI) ratios, and other critical metrics.
* Identification of high-risk loan categories and borrower segments.
* Detailed visualization of default probabilities across various factors.

# Analysis Steps

* Data Cleaning:
  * Handled missing values through imputation based on column type and context.
  * Renamed columns for clarity and consistency.

* Exploratory Data Analysis (EDA):
  * Analyzed distributions of categorical and numerical variables.
  * Derived key metrics such as Loan Amount Bins, Credit Score Categories, and DTI Ratios.

* Segmentation:
  * Segmented borrowers by age, income, and region to identify high-risk groups.

* Correlation Analysis:
  * Assessed relationships between numerical variables and default status.
  * Created heatmaps for a visual summary of correlations.

* Multivariate Analysis:
  * Analyzed default probabilities by Loan Type, Loan Purpose, and Business/Commercial status using pivot tables and heatmaps.

* Risk Assessment:
  * Evaluated the impact of LTV, upfront charges, and DTI on default rates.
  * Segmented defaulters by credit type and geographic region.

# Key Insights

* Loan Purpose Matters:
  * Loans for purpose p2 exhibit the highest default rate across all loan types.
  * Purpose p4 loans are the least risky.
   
* Income and Credit Score Interaction:
  * Borrowers with lower income and "Fair" credit scores are more likely to default.
   
* DTI and Risk:
  * High DTI (>80%) borrowers have a significantly higher default rate (33%).
   
* Impact of Upfront Charges:
  * High upfront charges mitigate default risk, particularly for high LTV loans.
   
* Regional Variations:
  * The North-East region shows uniformly high default rates, necessitating targeted interventions.

# Conclusion

This analysis highlights the critical role of borrower characteristics and loan features in predicting loan defaults. The findings can be leveraged to:
* Improve credit scoring models.
* Develop targeted risk mitigation strategies.
* Enhance lending policies to minimize defaults.

# Tools & Libraries Used

o Pandas: Data manipulation and analysis.

o NumPy: Numerical operations.

o Seaborn & Matplotlib: Data visualization.

o Scikit-learn: Data preprocessing.

