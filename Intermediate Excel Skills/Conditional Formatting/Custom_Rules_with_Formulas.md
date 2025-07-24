# Custom Rules with Formulas in Excel

## Overview
Custom conditional formatting rules use formulas to highlight cells based on complex conditions, a key intermediate skill for interviews.

## Key Concepts
- **Custom Rule**: Home > Conditional Formatting > New Rule > Use a formula.
- **Formula Logic**: Must return TRUE/FALSE for each cell.
- **Examples**:
  - `=A1>100`: Highlights cells >100.
  - `=AND(A1>50, B1<200)`: Combines conditions.
- **Relative References**: Adjust automatically for each cell.

## Step-by-Step Example
**Scenario**: Highlight rows where sales >1000 and region is “North”.
1. **Prepare Data**:
   - Columns: Region (A2:A20), Sales (B2:B20).
2. **Create Rule**:
   - Select A2:B20.
   - Home > Conditional Formatting > New Rule > Use a formula.
   - Enter `=AND(A2="North", B2>1000)`.
   - Set format to Yellow Fill.
3. **Apply**: Click OK; rows meeting both conditions are highlighted.

## Practical Scenario
You have a dataset with products, prices, and quantities. Highlight rows where price >$50 and quantity <10.

## Practice Tasks
1. Highlight cells where sales are above average (`=B2>AVERAGE(B:B)`).
2. Highlight rows where category is “Electronics” and sales >500.
3. Use a formula to highlight every other row (`=MOD(ROW(),2)=0`).
4. Highlight cells with negative values.
5. Combine `AND` and `OR` in a custom rule.

## Interview Tip
Interviewers may test formula-based formatting. Practice writing and explaining custom formulas.