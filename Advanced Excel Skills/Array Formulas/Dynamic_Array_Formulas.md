# Dynamic Array Formulas in Excel

## Overview
Dynamic Array Formulas (FILTER, SORT, UNIQUE) automatically spill results, simplifying advanced calculations for interviews.

## Key Functions
- **FILTER**: `=FILTER(A2:B100, B2:B100>1000)` – Filter data by condition.
- **SORT**: `=SORT(A2:A100)` – Sort data dynamically.
- **UNIQUE**: `=UNIQUE(A2:A100)` – Extract unique values.

## Step-by-Step Example
**Scenario**: Filter and sort high sales.
1. **FILTER**:
   - Data: Product (A2:A100), Sales (B2:B100).
   - In C2, enter `=FILTER(A2:B100, B2:B100>1000)`.
   - Result: Spills products with sales >1000.
2. **SORT**:
   - In E2, enter `=SORT(B2:B100, 1, -1)` for descending order.
3. **UNIQUE**:
   - In G2, enter `=UNIQUE(A2:A100)` for unique products.

## Practical Scenario
You have a dataset of employees (name, department, salary). Use FILTER for salaries >$50,000, SORT by salary, and UNIQUE for departments.

## Practice Tasks
1. Use FILTER to show sales >500 in a region.
2. Sort a column of dates dynamically.
3. Extract unique customer IDs with UNIQUE.
4. Combine FILTER and SORT for a sorted filtered list.
5. Test dynamic arrays with changing data.

## Interview Tip
Interviewers may test modern formulas. Practice dynamic arrays for efficient data manipulation.