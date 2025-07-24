# Logical Functions in Excel

## Overview
Logical functions enable decision-making in Excel. This guide covers IF, AND, and OR functions for data analysis.

## Key Functions
- **IF**: `=IF(condition, value_if_true, value_if_false)` – Returns value based on condition.
- **AND**: `=AND(condition1, condition2)` – True if all conditions are met.
- **OR**: `=OR(condition1, condition2)` – True if any condition is met.

## Step-by-Step Example
**Scenario**: Categorize sales performance.
1. **IF for Sales Threshold**:
   - Data: Sales in A2:A10.
   - In B2, enter `=IF(A2>1000, "High", "Low")`.
   - Drag down to B10.
2. **AND for Multiple Conditions**:
   - In C2, enter `=AND(A2>500, A2<1000)` to check moderate sales.
3. **OR for Flexible Criteria**:
   - In D2, enter `=OR(A2>1000, A2<200)` for extreme sales.

## Practical Scenario
You have employee data with salaries and years of service. Flag employees with salary >$50,000 and service >5 years using `AND` within `IF`.

## Practice Tasks
1. Use `IF` to flag orders >$2000 as “Priority”.
2. Combine `AND` with `IF` to mark sales between 100 and 500.
3. Use `OR` to identify extreme values (<50 or >1000).
4. Nest `IF` statements to categorize sales as High, Medium, Low.
5. Create a formula to flag invalid data (e.g., negative values).

## Interview Tip
Interviewers may ask for conditional logic. Practice nesting functions and explaining your logic clearly.