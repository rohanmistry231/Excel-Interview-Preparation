# Data Tables for Sensitivity Analysis in Excel

## Overview
Data Tables perform sensitivity analysis by testing multiple variable combinations, useful for interviews.

## Key Concepts
- **Data Table**: Data > What-If Analysis > Data Table.
- **Types**:
  - One-Variable: Test one input.
  - Two-Variable: Test two inputs.
- **Setup**: Link to a formula model.

## Step-by-Step Example
**Scenario**: Analyze profit with varying sales and costs.
1. **Setup Model**:
   - B1: Sales, B2: Cost, B3: Profit (`=B1-B2`).
2. **Create Data Table**:
   - Column D2:D10: Sales values (1000, 2000, ...).
   - Row C1:J1: Cost values (500, 600, ...).
   - In C2, enter `=B3`.
   - Select C1:J10, Data > What-If Analysis > Data Table.
   - Row Input: B2, Column Input: B1.

## Practical Scenario
Test loan payments with varying interest rates and terms using a two-variable Data Table.

## Practice Tasks
1. Create a one-variable Data Table for sales impact.
2. Build a two-variable Data Table for price and quantity.
3. Link a Data Table to a complex formula.
4. Format a Data Table for clarity.
5. Analyze Data Table results for trends.

## Interview Tip
Interviewers may ask for sensitivity analysis. Practice Data Tables to show variable impacts.