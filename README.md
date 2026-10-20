# Telecom Customer Churn: Statistical Analysis

Churn analysis of 7,043 telecom customers in R, including a test of whether the churn rate exceeds 25%.

## What the script does

`Churn_Analysis.R` goes through:

- **Cleaning:** checking missing values and filling missing `TotalCharges` with the mean
- **Descriptive statistics:** shares of senior citizens, partners, dependents, paperless billing, gender and more
- **Churn by group:** bar charts of churn rate by phone service, online security, online backup, contract type and payment method
- **Trends:** churn rate across binned tenure and monthly-charge groups
- **Inference:** a 95% confidence interval for the churn rate, and a one-sided z-test of H₀: p = 0.25 against H₁: p > 0.25

## Data

The script reads `Churn.csv`, the Telco Customer Churn dataset (7,043 customers). The file isn't included in this repo, so download it and place it next to the script.

## Running

```r
source("Churn_Analysis.R")
```

Only base R is used.
