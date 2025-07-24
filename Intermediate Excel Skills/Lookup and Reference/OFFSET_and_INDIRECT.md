# OFFSET and INDIRECT in Excel

## Overview
OFFSET and INDIRECT create dynamic references, useful for advanced analysis and interviews.

## Key Functions
- **OFFSET**: `=OFFSET(reference, rows, cols, [height], [width])` – Returns a dynamic range.
- **INDIRECT**: `=INDIRECT(ref_text)` – References a cell or range by text.

## Step-by-Step Example
**Scenario**: Create a dynamic sum based on user input.
1. **OFFSET**:
   - Data: Sales in B2:B100.
   - In C1, enter number of rows (e.g., 5).
   - In D1, enter `=SUM(OFFSET(B2, 0, 0, C1, 1))` to sum first 5 rows.
2. **INDIRECT**:
   - In E1, enter sheet name (e.g., “Sheet1”).
   - In F1, enter `=INDIRECT(E1 & "!B2")` to reference B2 on Sheet1.

## Practical Scenario
You have monthly sales in different sheets. Use INDIRECT to pull data from a specified sheet and OFFSET to sum a dynamic range.

## Practice Tasks
1. Use OFFSET to sum the last 10 rows of data.
2. Use INDIRECT to reference a cell in another sheet.
3. Combine OFFSET with COUNT for dynamic ranges.
4. Create a dynamic chart range with OFFSET.
5. Test INDIRECT with a dropdown list of sheet names.

## Interview Tip
Interviewers may test dynamic referencing. Practice OFFSET for ranges and INDIRECT for cross-sheet tasks.