# Loan Default Analysis
## Objective
Develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimize the risk of losing money while lending to customers.This project provides an opportunity to enhance risk assessment strategies in lending institutions, leading to more informed decision-making and proactive default prevention measures.
## Important Links
- [Dataset](https://drive.google.com/drive/folders/1cz3JUsfXDXPh2AM6FhEVQHvt5aZhveBU?usp=drive_link)
- [Jupyter Notebooks](https://github.com/shyammanikandan/Loan_Default_Analysis/tree/main/Notebooks)
- [Tableau Dashboard](https://public.tableau.com/app/profile/shyam8567/viz/LoanDefault_17283986543180/Dashboard1)
- [Project Report](https://docs.google.com/presentation/d/1SlWIkXRk8zmBntbrP0avMm_VsSE03N5b/edit?usp=sharing&ouid=112919458368926806580&rtpof=true&sd=true)
## About Data
The loan default dataset contains detailed information about loans that have either been repaid or defaulted. Each record represents an individual loan, with a variety of associated attributes, such as loan limit, loan purpose, loan amount, rate of interest, income, region of the borrower and more.

### Features of the Loan Default Dataset
| Feature                      | Description |
| -----------                  | ----------- |
| Id                           | Id for each row |
| Year                         | Year when loan was taken|
| Loan limit                   | If loan limit is fixed or variable|
| Gender                       | Gender of applicant|
| Loan type                    | Type of loan (masked data)|
| Loan purpose                 | Purpose of loan (masked data)|
| Business or Commercial       | Business or Personal loan|
| Loan amount                  | Total loan amount       |
| Rate of interest             | Interest on loan        |
| Upfront Charges              | Down Payment       |
| Property value               | Value of Property        |
| Occupancy type               | Type of establishment       |
| Income                       | Income of applicant              |
| Credit type                  | 'EXP' 'EQUI' 'CRIF' 'CIB'      |
| Credit score                 | Credit score of applicant        |
| Co-applicant credit type     | Credit type of co-applicant       |
| Age                          | Age of applicant        |
| LTV                          | Lifetime value of applicant       |
| Region                       | Region of applicant        |
| Status                       | Defaulter(1) or Compliant(0)        |

## Data Cleaning

- There are 148670 unique records in the dataset.
- Few columns have missing values and outliers.
- Missing values are treated by mode and mean of the columns.
- Outliers are treated by Inter Quartile Range.

## Tests and Concepts used

- Chi-square Test for Independence
- One Way ANOVA
- QQ - plot to test normality of data
- Shapiro Wilk test to test normality of data
- Levene's Test to test the variance among the groups
- Central Limit Theorem
- Random Sampling
- Correlation Matrix

## Trends and Insights

- Loan products under the Type 1 category are likely contributing disproportionately to the overall default rate.
- Purpose-driven loans (P3, P4) might require more stringent risk assessments, especially in uncertain economic climates.
- Geographic location has a significant impact on default risk, likely due to regional economic factors.
- High Loan Amounts Are Correlated with Higher Default Rates.
- Borrowers with personal and fixed-rate loans may face higher default risks.

## Business Recommendations

- Consider offering financial literacy programs or pre-loan counseling to help borrowers understand the loan terms and consequences of default.
- Implement more thorough risk assessments for P3 and P4 loans.
- Consider developing region-specific financial products that take into account local economic conditions.
- Offer smaller loan products with more affordable repayment plans for high-risk borrowers.
- Reassess the pricing model and risk criteria for personal loans, potentially increasing requirements for borrower eligibility.
