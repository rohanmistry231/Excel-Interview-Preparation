# Creating User-Defined Functions in VBA

## Overview
User-Defined Functions (UDFs) create custom Excel formulas, enhancing analysis for interviews.

## Key Concepts
- **UDF Syntax**: `Function` instead of `Sub`.
- **Access**: Use in cells like built-in functions.
- **Scope**: Save in module for workbook-wide use.

## Step-by-Step Example
**Scenario**: Create a UDF to calculate commission (10% of sales).
1. **Write UDF**:
   ```vba
   Function CalcCommission(sales As Double) As Double
       CalcCommission = sales * 0.1
   End Function
   ```
2. **Use in Excel**:
   - In B2, enter `=CalcCommission(A2)` where A2 is sales value.

## Practical Scenario
Create a UDF to calculate tax (5% for sales >1000, 3% otherwise).

## Practice Tasks
1. Create a UDF to calculate profit (sales - cost).
2. Write a UDF for custom text concatenation.
3. Build a UDF to round numbers to nearest 10.
4. Test a UDF with multiple arguments.
5. Debug a UDF with incorrect inputs.

## Interview Tip
Interviewers may ask for custom formulas. Practice writing and testing UDFs in Excel.