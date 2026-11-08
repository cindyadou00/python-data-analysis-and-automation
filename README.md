# Python Data Analysis and Automation

## Project Overview

This academic Python project demonstrates the use of Python and Pandas to automate data validation, process datasets, perform statistical analysis, and export results into Excel files.

The project is divided into two main sections:

1. **Password Validation Analysis**
2. **Credit Risk and Loan Analysis**

## 1. Password Validation Analysis

### Objective

Develop a Python-based password validation process to evaluate whether passwords meet predefined security requirements.

### Methodology

The program checks three conditions:

- Minimum password length of 12 characters.
- Presence of at least one uppercase letter.
- Presence of at least one special character from `@`, `(`, `)` or `&`.

Two validation approaches are implemented:

- **Detailed Validation:** Identifies unmet password requirements and provides explanatory error messages.
- **Binary Validation:** Classifies passwords as `Yes` or `No` based on whether they meet all requirements.

Results are processed using Pandas and exported to CSV or Excel.

## 2. Credit Risk and Loan Analysis

### Objective

Analyze loan application data to explore lending patterns, credit scores, interest rates, and the relationship between previous loan defaults and approval outcomes.

### Dataset

The analysis uses a loan dataset containing 45,000 observations and 14 variables.

### Analytical Tasks

**1. Loan Amount Analysis by Purpose**

Calculate descriptive statistics for approved loan amounts, including minimum, first quartile, mean, third quartile, and maximum.

**2. Interest Rate Analysis by Loan Purpose**

Compare minimum and maximum interest rates and calculate their range across different loan purposes.

**3. Credit Score Analysis by Default History**

Examine credit score distributions for applicants with and without previous loan defaults.

**4. Loan Approval Analysis by Default History**

Analyze loan approval and rejection counts according to applicants' previous default history.

**5. Average Approved Loan Amount for High Credit Scores**

Calculate average approved loan amounts by loan purpose for applicants with credit scores of at least 700.

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- Microsoft Excel
- CSV data processing

## Skills Demonstrated

- Data loading and manipulation
- Conditional logic and Python functions
- Automated data validation
- Data filtering and grouping
- Descriptive statistics
- Financial and credit data analysis
- Excel and CSV reporting
- Basic exception handling

## Project Context

This project was developed as part of academic Python coursework. It demonstrates foundational programming, data analysis, and reporting techniques through practical exercises.

## Future Improvements

- Add data visualizations to support the financial analysis.
- Introduce additional data quality checks.
- Improve code organization and portability.
- Expand the interpretation of credit risk indicators.