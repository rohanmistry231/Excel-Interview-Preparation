# INDEX and MATCH in Excel

## Overview
INDEX and MATCH offer a flexible alternative to VLOOKUP, ideal for complex lookups in interviews.

## Key Functions
- **INDEX**: `=INDEX(array, row_num, [col_num])` – Returns value at specified position.
- **MATCH**: `=MATCH(lookup_value, lookup_array, [match_type])` – Finds position of a value.
- **Combined**: `=INDEX(B2:B10, MATCH(D2, A2:A10, 0))` – Dynamic lookup.

## Step-by-Step Example
**Scenario**: Find product prices by ID.
1. **Prepare Data**:
   - Columns: ID (A2:A10), Price (B2:B10).
2. **MATCH**:
   - In E2, enter `=MATCH(D2, A2:A10, 0)` to find row of ID in D2.
3. **INDEX**:
   - In F2, enter `=INDEX(B2:B10, E2)` to get price.
4. **Combine**:
   - In G2, enter `=INDEX(B2:B10, MATCH(D2, A2:A10, 0))`.

## Practical Scenario
You have a dataset with employee IDs, names, and salaries. Use INDEX and MATCH to retrieve salaries by ID.

## Practice Tasks
1. Use INDEX and MATCH to find product names by code.
2. Perform a two-way lookup (row and column).
3. Handle errors with `IFERROR`.
4. Compare VLOOKUP vs. INDEX/MATCH performance.
5. Use MATCH with approximate match type (1 or -1).

## Interview Tip
Interviewers may prefer INDEX/MATCH for flexibility. Practice explaining why it’s more versatile than VLOOKUP.