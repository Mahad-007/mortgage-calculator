# Mortgage Repayments Calculator

This is a simple **mortgage repayments calculator** built using **Streamlit**, which helps users calculate their monthly mortgage payments, total repayment amount, and total interest paid over the life of the loan.

The app also provides a **payment schedule** and a **line chart** showing how the remaining loan balance decreases over time.

## Features

- **Input Fields**:
  - Home Value (Total cost of the property)
  - Deposit (Initial down payment)
  - Interest Rate (%) (Annual interest rate for the loan)
  - Loan Term (Years)

- **Calculated Metrics**:
  - Monthly Repayment
  - Total Repayments
  - Total Interest Paid

- **Payment Schedule**: View how the loan balance decreases over time with monthly payments for principal and interest.

- **Graph**: A **line chart** that shows how the remaining balance decreases each year.

## How It Works

1. The app calculates the loan amount:  
   **Loan Amount = Home Value - Deposit**.
2. It then calculates the **monthly payment** using the standard loan formula.
3. The app displays the **total repayments** and the **total interest** paid over the entire loan period.
4. A detailed **payment schedule** is generated showing how much principal and interest are paid each month.
5. A **line chart** visualizes the reduction in the loan balance over the years.

## Requirements

- Python 3.x
- Streamlit
- pandas
- matplotlib

