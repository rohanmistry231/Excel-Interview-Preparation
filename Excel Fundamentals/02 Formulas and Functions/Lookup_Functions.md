# Lookup Functions in Excel

## Overview
Lookup functions retrieve data from tables. This guide covers VLOOKUP and HLOOKUP.

## Key Functions
- **VLOOKUP**: `=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])` – Vertical lookup.
- **HLOOKUP**: `=HLOOKUP(lookup_value, table_array, row_index_num, [range_lookup])` – Horizontal lookup.
- **Range Lookup**: `FALSE` for exact match, `TRUE` for approximate.

## Step-by-Step Example
**Scenario**: Find product prices in a table.
1. **Setup Data**:
   - Table: Product ID (A2:A10), Price (B2:B10).
2. **VLOOKUP**:
   - In C2, enter `=VLOOKUP(D2, A2:B10, 2, FALSE)` to find price for ID in D2.
3. **HLOOKUP**:
   - Table: Months (B1:M1), Sales (B2:M2).
   - In B3, enter `=HLOOKUP("Jan", B1:M2, 2, FALSE)` to get January sales.

## Practical Scenario
You have a product catalog with IDs and prices. Use `VLOOKUP` to retrieve prices for a list of ordered IDs.

## Practice Tasks
1. Use `VLOOKUP` to find employee salaries by ID.
2. Apply `HLOOKUP` to get sales for a specific month.
3. Test exact vs. approximate matches in `VLOOKUP`.
4. Handle errors with `IFERROR` in lookups.
5. Combine `VLOOKUP` with another function (e.g., `SUM`).

## Interview Tip
Interviewers may test lookup accuracy. Practice exact matches and handling missing data.