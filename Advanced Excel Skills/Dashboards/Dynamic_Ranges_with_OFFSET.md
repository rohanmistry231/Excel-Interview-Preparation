# Dynamic Ranges with OFFSET in Excel

## Overview
Dynamic ranges using OFFSET adapt charts and tables to changing data, a valuable skill for interviews.

## Key Concepts
- **OFFSET**: `=OFFSET(reference, rows, cols, [height], [width])`.
- **Named Ranges**: Define dynamic ranges (Formulas > Name Manager).
- **Use Cases**: Charts, Pivot Tables, dashboards.

## Step-by-Step Example
**Scenario**: Create a dynamic chart range.
1. **Setup Data**:
   - A1:B100: Month, Sales.
2. **Define Named Range**:
   - Formulas > Name Manager > New.
   - Name: “DynamicSales”, Formula: `=OFFSET(Sheet1!$B$2,0,0,COUNT(Sheet1!$B$2:$B$100),1)`.
3. **Create Chart**:
   - Insert Chart using named range “DynamicSales”.

## Practical Scenario
Create a dashboard with a dynamic chart that updates as new sales data is added.

## Practice Tasks
1. Create a dynamic range for a sales column.
2. Use OFFSET in a chart data source.
3. Define a named range for a Pivot Table.
4. Test dynamic range with new data.
5. Combine OFFSET with COUNTIF for conditional ranges.

## Interview Tip
Interviewers may ask for adaptable dashboards. Practice OFFSET for dynamic data sources.