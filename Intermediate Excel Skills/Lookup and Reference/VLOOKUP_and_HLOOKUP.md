# VLOOKUP and HLOOKUP in Excel

## Overview
VLOOKUP and HLOOKUP retrieve data from tables, widely used in data analysis and interviews.

## Key Functions
- **VLOOKUP**: `=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])` – Vertical lookup.
- **HLOOKUP**: `=HLOOKUP(lookup_value, table_array, row_index_num, [range_lookup])` – Horizontal lookup.
- **Range Lookup**: `FALSE` for exact match, `TRUE` for approximate.

## Step-by-Step Example
**Scenario**: Find product prices and monthly sales.
1. **VLOOKUP**:
   - Data: Product ID (A2:A10), Price (B2:B10).
   - In C2, enter `=VLOOKUP(D2, A2:B10, 2, FALSE)` to find price for ID in D2.
2. **HLOOKUP**:
   - Data: Months (B1:M1), Sales (B2:M2).
   - In B3, enter `=HLOOKUP("Jan", B1:M2, 2, FALSE)` to get January sales.

## Practical Scenario
You have a product catalog (ID, Name, Price) and sales data by month. Use VLOOKUP to get prices and HLOOKUP for monthly totals.

## Practice Tasks
1. Use VLOOKUP to find employee names by ID.
2. Apply HLOOKUP to get quarterly sales.
3. Test exact vs. approximate matches.
4. Handle errors with `IFERROR(VLOOKUP(...), "Not Found")`.
5. Combine VLOOKUP with SUM for total price of multiple items.

## Interview Tip
Interviewers may test lookup accuracy. Practice exact matches and error handling.