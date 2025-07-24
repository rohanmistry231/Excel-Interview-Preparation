# Multi-Cell Calculations with Array Formulas

## Overview
Multi-cell array formulas perform complex calculations across ranges, useful for advanced analysis and interviews.

## Key Concepts
- **Dynamic Arrays**: Spill results automatically (Excel 365).
- **Legacy Arrays**: Ctrl+Shift+Enter for fixed ranges.
- **Examples**: Combine conditions, math operations.

## Step-by-Step Example
**Scenario**: Calculate total revenue per product.
1. **Setup Data**:
   - Product (A2:A100), Quantity (B2:B100), Price (C2:C100).
2. **Dynamic Array**:
   - In D2, enter `=B2:B100*C2:C100` (spills results).
3. **Legacy Array**:
   - Select D2:D100, enter `=B2:B100*C2:C100`, press Ctrl+Shift+Enter.

## Practical Scenario
Calculate profit (sales - cost) for multiple products using an array formula, then filter for positive profits.

## Practice Tasks
1. Multiply two columns with a dynamic array.
2. Use a legacy array for conditional sums.
3. Combine arrays with FILTER for complex criteria.
4. Test array formulas with large datasets.
5. Debug multi-cell array errors.

## Interview Tip
Interviewers may test complex calculations. Practice array formulas for efficient data processing.