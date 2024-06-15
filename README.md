# Personal Loan Eligibility Checker

## Detailed Business Requirements for Personal Loan Application

As a Product Manager, here are the detailed business requirements for a Personal Loan Eligibility Checker for a banking application. These requirements will help in writing test cases and developing the `PersonalLoanEligibilityChecker` class.

### 1. Loan Amount Validation

**Requirement:** The loan amount requested by the applicant must be within the allowable range.

- **Minimum Loan Amount:** $1,000
- **Maximum Loan Amount:** $100,000

### 2. Credit Score Validation

**Requirement:** The applicant’s credit score must meet the minimum threshold to be eligible for a loan.

- **Minimum Credit Score:** 600

### 3. Income and Debt-to-Income Ratio Validation

**Requirement:** The applicant’s monthly income and debt-to-income ratio will be used to determine eligibility.

- **Minimum Monthly Income:** $2,000
- **Maximum Debt-to-Income Ratio:** 40%

### 4. Interest Rate Calculation

**Requirement:** The interest rate for the loan will be determined based on the applicant’s credit score.

- **Credit Score 600-649:** 8%
- **Credit Score 650-699:** 6%
- **Credit Score 700-749:** 4%
- **Credit Score 750 and above:** 3%

### 5. Monthly Payment Calculation

**Requirement:** The monthly payment for the loan should be calculated using the following formula:
\[ M = \frac{P \times r \times (1+r)^n}{(1+r)^n - 1} \]

- **P:** Principal loan amount
- **r:** Monthly interest rate (annual rate / 12 / 100)
- **n:** Loan term in months

### 6. Loan Term Options

**Requirement:** The applicant can choose the loan term.

- **Available Terms:** 12 months, 24 months, 36 months, 48 months, 60 months

### 7. Eligibility Determination

**Requirement:** The applicant is eligible for the loan if all the above conditions are met.

- Valid loan amount
- Sufficient credit score
- Acceptable debt-to-income ratio
- Adequate monthly income
