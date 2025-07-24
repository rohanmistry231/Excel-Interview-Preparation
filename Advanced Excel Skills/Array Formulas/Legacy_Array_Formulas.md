# Legacy Array Formulas in Excel

## Overview
Legacy Array Formulas (Ctrl+Shift+Enter) handle complex calculations in older Excel versions, still relevant for interviews.

## Key Concepts
- **Syntax**: Enter with Ctrl+Shift+Enter (curly braces appear).
- **Use Cases**: Multi-cell calculations, conditional sums.
- **Example**: `=SUM(IF(A2:A100="North", B2:B100))`.

## Step-by-Step Example
**Scenario**: Sum sales for “North” region.
1. **Setup Data**:
   - Region (A2:A100), Sales (B2:B100).
2. **Legacy Array Formula**:
   - In C2, enter `=SUM(IF(A2:A100="North", B2:B100))`.
   - Press Ctrl+Shift+Enter.
3. **Verify**: Check sum against manual calculation.

## Practical Scenario
Calculate average sales for products with quantities >10 using a legacy array formula.

## Practice Tasks
1. Sum sales for a specific category with an array formula.
2. Calculate max value for filtered data.
3. Use an array formula with multiple conditions.
4. Test legacy vs. dynamic arrays.
5. Debug an array formula error.

## Interview Tip
Interviewers may test compatibility knowledge. Practice legacy arrays for older Excel versions.