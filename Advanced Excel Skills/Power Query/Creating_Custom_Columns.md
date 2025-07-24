# Creating Custom Columns in Power Query

## Overview
Custom columns in Power Query add calculated fields to datasets, enhancing analysis capabilities for interviews.

## Key Concepts
- **Add Column**: Home > Add Column > Custom Column.
- **Formula**: Use Power Query’s M language (e.g., `[Sales] * 0.1`).
- **Common Uses**: Calculations, conditional logic, text manipulation.
- **Preview**: See results in Query Editor.

## Step-by-Step Example
**Scenario**: Add a profit column to sales data.
1. **Import Data**:
   - Load `sales.csv` (Product, Sales, Cost).
2. **Add Custom Column**:
   - In Query Editor, Add Column > Custom Column.
   - Name: “Profit”, Formula: `[Sales] - [Cost]`.
3. **Conditional Column**:
   - Add Column > Conditional Column.
   - Name: “Status”, If `[Profit] > 0` then “Positive” else “Negative”.

## Practical Scenario
You have sales data with quantities and prices. Add a custom column for total revenue and another for high/low sales status.

## Practice Tasks
1. Create a custom column for 10% commission.
2. Add a conditional column for sales >1000.
3. Calculate a custom date column (e.g., add 30 days).
4. Combine text columns in a custom column.
5. Test custom columns with complex logic.

## Interview Tip
Interviewers may test custom calculations. Practice creating and explaining custom columns.