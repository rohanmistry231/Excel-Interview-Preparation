# Calculated Fields in Pivot Tables

## Overview
Calculated Fields add custom calculations to Pivot Tables, enhancing analysis capabilities.

## Key Concepts
- **Insert Calculated Field**: PivotTable Analyze > Fields, Items & Sets > Calculated Field.
- **Formula**: Use existing fields (e.g., `=Sales*0.1` for 10% commission).
- **Limitations**: Cannot use cell references, only Pivot Table fields.

## Step-by-Step Example
**Scenario**: Add a commission field (10% of sales).
1. **Create Pivot Table**:
   - Data: Product (A), Sales (B).
   - Insert Pivot Table with Product in Rows, Sales in Values.
2. **Add Calculated Field**:
   - PivotTable Analyze > Fields, Items & Sets > Calculated Field.
   - Name: “Commission”, Formula: `=Sales*0.1`.
   - Click Add, then OK.
3. **View Results**: New column shows commission values.

## Practical Scenario
You have sales and cost data. Add a Calculated Field for profit (Sales - Cost) in a Pivot Table.

## Practice Tasks
1. Add a 5% tax field to a sales Pivot Table.
2. Calculate profit margin (Profit/Sales) in a Pivot Table.
3. Create a bonus field (Sales >1000 get $50).
4. Test multiple Calculated Fields in one Pivot Table.
5. Update a Calculated Field formula.

## Interview Tip
Interviewers may ask for custom calculations. Practice creating and explaining Calculated Fields.